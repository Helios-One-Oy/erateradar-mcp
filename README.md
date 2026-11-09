# erateradar MCP

erateradar connects Claude and ChatGPT to public USAC E-rate data for IT, network and cabling providers. Ask for open Category 2 Form 470s (school and library Wi-Fi, switches, cabling, firewalls, UPS) within up to 60 miles of a ZIP or city, or in a state; open one Form 470 with every requested line item as USAC lists it; or see what a buyer reported on its previous request: bids received, the provider it chose, the pre-discount cost and the USAC status. Every row links to its USAC Open Data record and to the same list in the erateradar web app. All tools are read-only and answer in pages of at most 25 rows. USAC records are self-reported and do not promise a purchase or a winning bid.

Connect at `https://erateradar.com/mcp` with OAuth 2.1, DCR, and PKCE S256:

- Claude: add a custom connector using the URL above.
- ChatGPT: add a remote MCP connector in developer mode.
- Claude Code: `claude mcp add --transport http erateradar https://erateradar.com/mcp` and authenticate.
- Cursor: add a streamable HTTP MCP server with the URL above.

Documentation: https://erateradar.com/docs/mcp  
Privacy: https://erateradar.com/security#mcp  
Terms: https://erateradar.com/terms  
Support: hello@erateradar.com
