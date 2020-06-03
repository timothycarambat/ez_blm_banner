# Black Lives Matter - Easy Banner

This is a simple customizable `<script>` that can be inserted into your site that will append a banner to the top of the page showing your solidarity and support for the [#BlackLivesMatter](https://twitter.com/Blklivesmatter) movement.

## How to Use
At the bottom of your HTML or website include a script tag like so
` <script type="text/javascript" src='https://blm-banner.s3-us-west-2.amazonaws.com/blm.js'></script>`

This script allows optional parameters to customize the banner to your brand and message.
| Parameter | Default                 |
|:---------:|-------------------------|
| position  | fixed                   |
| bgColor   | #000                    |
| textColor | #FFF                    |
| msg       | We Stand In Solidarity. |

The parameters `position`, `bgColor`,and `textColor` all accept CSS parameters as you would normally expect. `msg` is simply a string. To use all of the params you would just add these parameters as query strings to the `src` attribute.

**Example**
`<script type="text/javascript" src='https://blm-banner.s3-us-west-2.amazonaws.com/blm.js?position=relative&bgColor=red&textColor=#FFF&msg=We Support Justice.'></script>`

![Image of Banner](https://github.com/timothycarambat/ez_blm_banner/screenshot.png)

The endpoint is an AWS bucket with CORS enabled so you may access it freely.
