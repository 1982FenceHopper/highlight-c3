# Highlight C3

Highlight C3 is an experimental project that showcases the potential capabilities of coupling AI and Predictive Analysis Algorithms with static, rudimentary data to understand trends and seasonal changes across various datasets, regardless of environments or scenarios

**_NOTE:_** **As of right now, a live webview is not available due to me having to work out many bugs and issues with the project, particularly the algorithms and the LLMs**

## Parts

This project is separated into three parts

1. **[The Aggregator](https://github.com/1982FenceHopper/highlight-c3-aggregator)** - The server that pulls statically available data from the [United Nations Food And Agriculture Organization](https://www.fao.org/home/en) and pulls the spreadsheet dataset to expose in a dynamic API endpoint.

2. **[The Hypothesizer](https://github.com/1982FenceHopper/highlight-c3-hypothesizer)** - The server that exposes a custom endpoint to use AI LLMs via Tool Calling to hypothesize data and trends for an accurate summary of future predictions (Courtesy of [Cloudflare Workers AI](https://www.cloudflare.com/developer-platform/products/workers-ai/)).

3. [**The Visualizer**](https://github.com/1982FenceHopper/highlight-c3-visualizer) - The Web UI that takes data from [1] and puts it in a locally hosted PostgreSQL database for quick referencing and data processing, and displaying it with future predictive data using algorithms, all the while requesting an hypothesis based on current data from [2].

## Languages and Frameworks

**The Aggregator**

- Express.js 4.21.0
- Decompress 4.2.1

**The Hypothesizer**

- ONNXruntime GPU 1.19.2
- Microsoft ONNXruntime GenAI 0.4.0

**The Visualizer**

- Next.js 15.0.2
- PostgreSQL 17.0

## Contributions

This project is in an heavy Alpha stage, and numerous bugs and issues need to be sorted out. That being said, any contributions to these aforementioned issues are greatly appreciated. If you wish to contribute, get in touch with me using my socials.

**Discord:** cursedmonolith<br>
**Instagram:** @1982fencehopper

## License

### This project is under the GNU AGPLv3 license, check `LICENSE` for more details.
