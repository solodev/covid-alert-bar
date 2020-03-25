# covid-alert-bar
Create custom alerts at the top of your homepage instantly

## Tutorial

For detailed instructions, view the [COVID Alert Bar](http://www.covidresponse19.com/free-website-tools/covid-alert-bar.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/g73a6cxk/).

## HTML

Add the HTML snippet to your templates or webpage, preferrably at the top above any navigation or header so that it has prominent positioning.

```
<div class="covid-alert">
   CORONAVIRUS (COVID-19) ALERTS: <a href="#">Click here for the latest information</a>
</div>
```


## CSS

Customize the background color and text/link colors by modifying the hexidecimal colors.

```
.covid-alert {
	background: #00a0dc;
	color: #fff;
	width: 100%;
	padding: 5px 10px;
	font-size: 16px;
	text-align: center;
	font-weight: bold;
	font-family: Inter, sans-serif;
}
.covid-alert a {
	color: #fff;
  text-decoration: underline;
  font-weight: 400;
}
```


