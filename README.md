# URL Shortner

## Description

This is a simple URL shortner that takes a long URL and returns a short URL. The short URL redirects to the long URL.

## Installation

1. Clone the repository
2. Run `pnpm install`
3. Run `pnpm dev`

## Usage

Use Postman to make a POST request to `http://localhost:8080/generate-shorturl` with the following body:

```json
{
    "url": "https://www.google.com"
}
```

The response will be:

```json
{
    "shortUrl": "http://localhost:8080/xyza"
}
```

You can then use the short URL to redirect to the long URL.

## License

[MIT](/LICENSE)
