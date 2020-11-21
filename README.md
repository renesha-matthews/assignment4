# Renesha Matthews
Fall Semester 2020 | MMC5277: Web Design Principles

## Media Queries
In order to optimize this code for different screens, use the follow `code`:

**Screen Resolution:** 1366 x 768
``` css
@media screen and (max-width: 1366px) {
    .wd-hero h1 {
        font: 200px 'Hacked', sans-serif;
        text-align: center;
        position: relative;
        bottom: 107px;
    }

    .about p {
      float: right;
      font: 18px 'Fira Code', monospace;
      line-height: 2.5em;
      position: absolute;
      top: 26%;
      right: 81px;
      width: 46%;
      text-shadow: 1px 1px 4px black;
    }
  }
```

**Screen Resolution:** 1440 x 900
``` css
@media screen and (max-width: 1440px) {
  .about h2 {
      float: right;
      position: relative;
      left: -21%;
      top: -46px;
  }

  .about p {
    float: right;
    font: 18px 'Fira Code', monospace;
    line-height: 2.5em;
    position: absolute;
    right: 81px;
    width: 42%;
    text-shadow: 1px 1px 4px black;
  }
}
```

### Troubleshooting
If media queries do not load properly, make sure to have the following `code` in the `<head>` tag in your HTML document:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

## Resources
* [CSS Media Queries](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp)
* [Download Hacked Font](https://watchdogsfont.com/)
* [CSS Media Query Troubleshooting](https://stackoverflow.com/questions/18207076/css-media-query-wont-work/18207189)


## Agreement
I, **Renesha Matthews**, have read the point deduction list and understand that I will lose points for missing items.

## Image
![Sitara](https://static.wikia.nocookie.net/watchdogscombined/images/a/a1/Sitara_render.jpg/revision/latest?cb=20161127225553)
