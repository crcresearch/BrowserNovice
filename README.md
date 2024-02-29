<a name="readme-top"></a>

<h3 align="center">Defending Novice User Privacy: An Evaluation of Default Web Browser Configurations</h3>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#experiment">Experiment Design</a>
        <ul>
          <li></li><a href="#prerequisites">Prerequisites</a></li>
          <li><a href="#privacytests">PrivacyTests.org</a></li>
          <li><a href="#browserleaks">Browser Leaks</a></li>
          <li><a href="#ptp">Privacy Test Pages</a></li>
        </ul>
    <li><a href="#evaluation">Evaluation</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is a part of the paper "Defending Novice User Privacy: An Evaluation of Default Web Browser Configurations" published in <i>Computers & Security</i> Journal. The paper can be found <a href="link">here</a>.

Cyber novices often enter sensitive data into web browsers for routine activities such as online shopping and bill payments, making them targets for malicious entities, including cybercriminals and oppressive governments. The proliferation of online advertising technologies further exacerbates privacy concerns by exploiting
user data for marketing or surveillance, frequently without explicit consent. It is crucial to regularly ensure the latest features of default configurations, which are most relevant for novice users, adequately address growing privacy demands given the centrality of web browsers to internet usage. Our work
scrutinizes the privacy claims of desktop browsers and their default configurations.

To ensure adequate experiment coverage, we used in-browser testing from three different toolkits on two operating systems, since browsers use local storage differently based on their platform.

Due to the frequent updates of browsers and operating systems, we will provide this repository for future researchers to utilize our analysis script and evaluate and report discrepancies in future versions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## Experiment Design

Below are the details needed to replicate our experiment. To evaluate the privacy of each browser, we leveraged in-browser tests from three different toolsets: PrivacyTests.org, BrowserLeaks, and Privacy Test Pages

### Prerequisites

To conduct the experiment, we recommend using different operating systems (we used an x86 CPU running Windows, version 11, and an Apple silicon M2 chip running MacOS, version Sonoma 14.1).

### PrivacyTests.org

PrivacyTests.org, available on GitHub or static results visible on their site was created and open-sourced by Dr. Arthur Edelstein (Usenix, 2023). 

### Browser Leaks

The BrowserLeaks (BrowserLeaks.com, 2011) toolkit offers a wide range of privacy and privacy tests designed to determine if websites engage in one of a variety of problematic practices, such as storing information about user devices, leaking real IP addresses, or performing browser fingerprinting on users.

### Privacy Test Pages

Privacy Test Pages, created by DuckDuckGo (Slayter), is an open-source toolkit available on GitHub for testing privacy and privacy features of browsers and browser extensions.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Kristina Radivojevic - kradivo2@nd.edu

Project Link: [https://github.com/crcresearch/BrowserNovice](https://github.com/crcresearch/BrowserNovice)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


