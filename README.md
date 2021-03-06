## Welcome to PESummary's public summarypages

This page contains summarypages generated with publically available data using
the [pesummary](https://lscsoft.docs.ligo.org/pesummary/) python package. All
command lines that were used to generate the webpages can be found on the
webpages themselves under the 'Downloads' tab. Details of the environment which
was used to generate the webpages can seen under the 'Version' tab.

<h3>
  <a href=./GW190412/home.html>GW190412 summarypages</a>
</h3>

These summarypages were generated with the
[publically available data](https://dcc.ligo.org/public/0163/P190412/008/posterior_samples.h5)
released through the [LIGO Document Control Center Portal](https://dcc.ligo.org).
This file can be downloaded with python by running the following,

```python
>>> import requests
>>> data = requests.get("https://dcc.ligo.org/public/0163/P190412/008/posterior_samples.h5")
>>> with open("posterior_samples.h5", "wb") as f:
...     f.write(data.content)
>>>
```

### Support or Contact

If you have any questions about this page or any of the data products listed
on this page, do not hesitate to email [Charlie Hoy](mailto:charlie.hoy@ligo.org).
