# Demo

https://demo-zoom.readthedocs.io/en/latest/


## There is more

But written for my eyes, not for a wider audience.

Hosting [this page](https://rtd-gcp-cloud.readthedocs.io/en/latest/), this documentation was made to assist with the Google Cloud Engineer Course.

## Build the site

1. My Ubuntu is set up with python and pip
2. Note this is pip3 `pip3 install -U sphinx`

3. [setup Sphinx](https://www.sphinx-doc.org/en/master/usage/quickstart.html)

4. build by running `make html` on the master folder (1 level above source and build)



## Helpful commands
Been using environment setup [not python virtual environment](https://towardsdatascience.com/virtual-environments-104c62d48c54?gi=7a13b3263f84)

`which sphinx-build` to see what executable is being called.

`ls -l /usr/local/bin/sphinx-build`

## Add RTD to GA

https://support.google.com/google-ads/gethelp

Admin, look at the Account column to make sure that you've selected the right account. Then, in the Property column, click Create Property.

https://support.google.com/analytics/answer/9304153?hl=en
case number is 7-8353000032280.

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-670QJ0R4KH"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-670QJ0R4KH');
</script>

