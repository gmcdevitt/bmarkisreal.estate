# bmarkisreal.estate

This is not so much a readme as a scratchpad if I forget what I did.

Theme docs: https://jpanther.github.io/congo/docs/

To get the agent reviews, I use the Bridge Interactive API: 
- https://bridgedataoutput.com/docs/platform/API/zg-data#agent-reviews
- https://bridgedataoutput.com/docs/explorer/zillow-agent-reviews#listZillowAgentReviews
  
The api key is stored in my bridge account.

It is parsed using Hugo's remote data functions
- https://gohugo.io/functions/resources/getremote/#remote-data
- https://gohugo.io/templates/lookup-order/#single-templates


Congo allows arbitrary content under the profile when using the profile mode for the home page. 
I instantly call into a shortcode that calls out to the bridge api and gets the reviews at that time.
It renders them as returned from the Bridge API.
