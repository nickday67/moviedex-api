# moviedex-api
# Requirements Create a project called moviedex-api and initialize it as an Express app to meet the following requirements.

# 1. Users can search for Movies by genre, country or avg_vote The endpoint is GET /movie
# 2. The search options for either name or type are provided in query string parameters.
# 3. When searching by genre, users are searching for whether the Movie's genre includes a             specified string. The search should be case insensitive.
# 4. When searching by country, users are searching for whether the Movie's country includes a         specified string. The search should be case insensitive.
# 5. When searching by average vote, users are searching for Movies with an avg_vote that is           greater than or equal to the supplied number.
# 6. The API responds with an array of full movie entries for the search results
# 7. The endpoint only responds when given a valid Authorization header with a Bearer API token        value.
# 8. The endpoint should have general security in place such as best practice headers and support      for CORS.