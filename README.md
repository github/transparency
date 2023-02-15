## GitHub Transparency Data

Transparency data about GitHub in structured data files.

## Background

### What is this?

Inspired by our [DMCA repo](https://github.com/github/dmca), which was inspired by [Lumen](https://lumendatabase.org/topics/1) (_formerly Chilling Effects_), this repo contains structured data files for the topics that we cover in our transparency report.

### Why is this?

To quote from [ourselves quoting others](https://github.com/github/dmca#why-is-this):

> In short, we believe that transparency on a specific and ongoing level is essential to good governance. Chilling Effects/Lumen explained it well in 2014 ([archive.org mirror; not present on their current site](https://web.archive.org/web/20140101160724/http://chillingeffects.org/#donato-if:~:text=We%20are%20excited%20about%20the%20new,its%20misuse%20to%20%22chill%22%20legitimate%20activity.)): "We are excited about the new opportunities the Internet offers individuals to express their views . . . but concerned that not everyone feels the same way. Study to date suggests that cease and desist letters often silence Internet users, whether or not their claims have legal merit." (About, ChillingEffects.org, Sept. 2014, licensed under [CC-BY-3.0](http://creativecommons.org/licenses/by/3.0/us/)). Similarly, we post takedown notices here to document their potential to "chill" speech.

### What's in this?

In addition to takedown notices, this repo contains data on the full range of sections in our transparency report, including:

- [Requests to disclose user information](data/requests_to_disclose_user_information)
  - Requests received
  - Disclosure and notification
  - National security letters and orders
  - Cross-border data requests
- [Government takedowns](data/government_takedowns)
- [DMCA takedowns](data/dmca)
  - Takedown notices received and processed
  - Projects affected by DMCA takedown requests
  - Circumvention claims
- [Automated detection](data/automated_detection)
- [Appeals and other reinstatements](data/appeals_and_other_reinstatements)
  - Abuse-related violations and appeals
  - Trade control appeals

### How do I use this?

Dive into the CSV files in the [data](data) directory using your favorite data analysis tools, like GitHub Codespaces, where the [default container image comes pre-installed with popular data science software packages](https://docs.github.com/en/codespaces/developing-in-codespaces/getting-started-with-github-codespaces-for-machine-learning#opening-the-image-classifier-notebook) such as Numpy, pandas, SciPy, Matplotlib, seaborn, scikit-learn, Keras, PyTorch, Requests, and Plotly. See [instructions for creating a Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).

## License

This project is licensed under the terms of the CC-BY-4.0 public license. Please refer to [LICENSE](./LICENSE.md) for the full terms.

## Maintainers

See [CODEOWNERS](CODEOWNERS)

## Support

See [SUPPORT](SUPPORT.md)
