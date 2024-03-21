<a name="readme-top"></a>

<h3 align="center">Defending Novice User Privacy: An Evaluation of Default Web Browser Configurations</h3>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#experiment">Experiment Design</a>
        <ul>
          <li><a href="#prerequisites">Prerequisites</a></li>
          <li><a href="#privacytests">PrivacyTests.org</a></li>
          <li><a href="#browserleaks">Browser Leaks</a></li>
          <li><a href="#ptp">Privacy Test Pages</a></li>
        </ul>
    <li><a href="#evaluation">Evaluation</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


## About The Project

This project is a part of the paper <b>"Defending Novice User Privacy: An Evaluation of Default Web Browser Configurations"</b> published in <i>Computers & Security</i> journal. The paper can be found [here](https://www.sciencedirect.com/science/article/pii/S0167404824000853).

Cyber novices often enter sensitive data into web browsers for routine activities such as online shopping and bill payments, making them targets for malicious entities, including cybercriminals and oppressive governments. The proliferation of online advertising technologies further exacerbates privacy concerns by exploiting
user data for marketing or surveillance, frequently without explicit consent. It is crucial to regularly ensure the latest features of default configurations, which are most relevant for novice users, adequately address growing privacy demands given the centrality of web browsers to internet usage. Our work
scrutinizes the privacy claims of desktop browsers and their default configurations.

Due to the frequent updates of browsers and operating systems, we provide this repository for future researchers to utilize our analysis script and evaluate and report discrepancies in future versions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Experiment Design

To evaluate the privacy of each browser, we leveraged in-browser tests from three different toolsets: PrivacyTests.org, BrowserLeaks, and Privacy Test Pages. 

### Prerequisites

To conduct the experiment and ensure adequate experiment coverage, we recommend using different operating systems (we used an x86 CPU running Windows, version 11, and an Apple silicon M2 chip running MacOS, version Sonoma 14.1), since browsers use local storage differently based on their platform.


### PrivacyTests.org

Download the repository from [https://github.com/privacytests/privacytests.org](https://github.com/privacytests/privacytests.org). PrivacyTests.org, available on GitHub or static results visible on their site was created and open-sourced by Dr. Arthur Edelstein. Run the program as explained on the README page in the repo. Consider the tests provided in the <i><b>Browser Metrics</i></b> file. 

### Browser Leaks

The BrowserLeaks toolkit can be found at [https://browserleaks.com/](https://browserleaks.com/). It offers a wide range of privacy and privacy tests designed to determine if websites engage in one of a variety of problematic practices, such as storing information about user devices, leaking real IP addresses, or performing browser fingerprinting on users. Run the tests provided in the <i><b>Browser Metrics</i></b> file. 

### Privacy Test Pages

Privacy Test Pages can be found at [https://github.com/duckduckgo/privacy-test-pages](https://github.com/duckduckgo/privacy-test-pages). Tests can also be found live at [https://privacy-test-pages.site/](https://privacy-test-pages.site/). This repository created by DuckDuckGo (Slayter), is an open-source toolkit available on GitHub for testing privacy and privacy features of browsers and browser extensions. Consider the tests provided in the <i><b>Browser Metrics</i></b> file. 


<p align="right">(<a href="#readme-top">back to top</a>)</p>



## Evaluation

We analyzed four Potentially Intrusive Practices (Behavioral Profiling, Fingerprinting, Targeted Advertising, and Reporting and Analytics) previously suggested in the work of [Smullen et al. (2021)](https://petsymposium.org/popets/2021/popets-2021-0082.php).

The script evaluates 14 browsers, it calculates metric scores of potentially intrusive particles and the composite score of privacy analysis. A higher score indicates more privacy in the default browser configuration. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the Apache License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Kristina Radivojevic - kradivo2@nd.edu

Project Link: [https://github.com/crcresearch/BrowserNovice](https://github.com/crcresearch/BrowserNovice)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


