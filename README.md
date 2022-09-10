
# Welcome to Youtube Comments Analyzer

A simple application built on top of Tiyaro API to showcase some NLP functions available on Tiyaro.

It uses the following Tiyaro models / APIs:
[Language detection](https://console.tiyaro.ai/explore/azure-1-cog-text-language-detect/api),
[Translation](https://console.tiyaro.ai/search/translation) and
[Sentiment Analysis](https://console.tiyaro.ai/search/sentiment%20analysis).
In addition, it uses Youtube IFrame and search / comments data APIs for loading Youtube video,
fetching video comments and finding related videos.

## backend

Nodejs based Apollo GraphQL server to provide two APIs:
- get related Youtube videos
- analyze comments for a Youtube video

## frontend

React + MUI based UI to show Youtube video, related videos, video comments analysis.

## License

[Apache License 2.0](LICENSE)
