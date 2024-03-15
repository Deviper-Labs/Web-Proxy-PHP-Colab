# Web-Proxy-PHP-Colab

# Disclamer:

> ⚠️ Unfortunately, Google Colab prohibits the use of their platform for services not related to interactive compute with Colab. As such, this notebook may suddenly terminate during process. Learn more in [Google Colab FAQ](https://research.google.com/colaboratory/faq.html).

---

<a target="_blank" href="https://colab.research.google.com/github/Deviper-Labs/Web-Proxy-PHP-Colab/blob/main/web.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Run a web proxy written in PHP through Google Colab made by [Deviper-Labs](https://github.com/Deviper-Labs)

---

## Note:
The actual proxy was created by [Athlon1600](https://github.com/Athlon1600), called [php-proxy](https://github.com/Athlon1600/php-proxy-app)

This notebook is just a way of using and setting up the same proxy on an online runtime via [Google Colab](https://research.google.com/colaboratory) and tunnelling it to an open server accessible from any device through the given URL

There is also a chance of getting a Regex error when running the last code cell and this occurs when the ngrok tunnel takes to long to open up and log the URL to the logging file for the regex to scan and retrieve the URL. To solve you can just try to re-run the cell.
