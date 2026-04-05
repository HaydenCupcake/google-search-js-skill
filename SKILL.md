name: google-search
description: Search Google and display the results. Use this skill when the user wants to search for something on Google or look something up online.
metadata:
  homepage: https://github.com/HaydenCupcake/Ten_Rand_Num
---

# Google Search

## Instructions

Call the `run_js` tool with the following exact parameters:
- script name: index.html
- data: A JSON string with the following field:
  - query: String. The search query to look up on Google.

After receiving the result, let the user know the search results are displayed below.
