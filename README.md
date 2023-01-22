# robots.txt templates

This is a collection of robots.txt templates

### What is robots.txt?

- Robots.txt is a file that tells search engines which pages or files the crawler can or can not request from your site

### What is a crawler?

- A crawler is a program that browses the web automatically. It is used by search engines to update their web index.

&nbsp;

## **Add a comment in robot.txt**

```text
# This is a comment
```

## **Allow all**

```text
User-agent: *
Allow: /
```

## **Disallow all**

```text
User-agent: *
Disallow: /
```

## **Block a folder**

```text
User-agent: *
Disallow: /folder/
```

## **Block a file**

```text
User-agent: *
Disallow: /file.html
```

## **Block a file type**

```text
User-agent: *
Disallow: /*.pdf$
```

## **Allow only Google**

```text
User-agent: *
Disallow: /

User-agent: Googlebot
Allow: /
```

## **Disallow only Google**

```text
User-agent: *
Allow: /

User-agent: Googlebot
Disallow: /
```

## **Link to your sitemap**

```text
User-agent: *
Sitemap: https://example.com/sitemap.xml
```

> The Sitemap directive tells the crawler where to find your sitemap.
>
> A sitemap is a file that lists the pages of your site. It is used by search engines to index your site.

## Slow down the crawler

```text
User-agent: *
Crawl-delay: 10
```

> The Crawl-delay directive tells the crawler to wait at least 10 seconds between requests to your site.

&nbsp;

---

## **User Agents**

- **Googlebot** - Used for Google Search
- **Bingbot** - Used for Bing Search
- **Slurp** - Yahoo's web crawler
- **DuckDuckBot** - Used by the DuckDuckGo search engine
- **Baiduspider** - This is a Chinese search engine
- **YandexBot** - This is a Russian search engine
- **facebot** - Used by Facebook
- **Pinterestbot** - Used by Pinterest
- **TwitterBot** - Used by Twitter
