<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->





<!-- PROJECT LOGO -->
<br />

https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/assets/130779672/c05e5453-7b17-4007-a257-8c800a37a2db



<h1 align="center">Customer Segmentation for effective marketing decisions with K-Means, DBSCAN and Gaussian Mixture Models</h1>




<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#data">DATA</a></li>
    <li><a href="#business-problem">Business Problem</a></li>
    <li><a href="#machine-learning-solutions">Machine Learning Solutions</a>
    <ul>
        <li><a href="#roadmap">Roadmap</a></li>
      </ul>
    </li>
    <li><a href="#conclusion-&-findings">Conclusion & Findings</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

To help a supermarket (a mall here) boost their membership card sign-up rate, I'll delve into various clustering methods to conduct a customer segmentation analysis. Customer segmentation involves identifying similar customer groups based on shared traits such as shopping habits and buying patterns, enabling companies to tailor marketing efforts more efficiently to each group. This notebook will entail building several clustering models to gain insights into the store's customer demographics and to devise tactics aimed at boosting membership sign-ups. The methods explored will include K-Means Clustering, Hierarchical Clustering, and DBSCAN
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/120px-Scikit_learn_logo_small.svg.png" alt="Sklearn Logo" width="100" height="50">
* <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/plotly-logo-vector.png" alt="Plotly Logo" width="100" height="50">
* <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/numpy-logo.svg" alt="Numpy Logo" width="100">
*  <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/python-horizontal.svg" alt="TensorFlow Logo" width="100">  
* <code><img width="50" src="https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png" alt="Jupyter Notebook" title="Jupyter Notebook"/></code>
* <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/pandas-logo.svg" alt="Pandas Logo" width="100">




<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Here I have focused on making the Exploratory Data Analysis part with interactive charts and plots. Also the clusters which will be visualizaed are interactive and if you are coding in colab then the following dependancy should be set first.

### Prerequisites

For having interactive charts using plotly in colab -
* Colab
  ```sh
  import plotly.io as pio
  pio.renderers.default = "colab"
  ```


<!-- DATA -->
## DATA

* The data set is sourced from https://www.kaggle.com/datasets

* It consists of 200 instances of customers data from a Mall in Europe consisting of 4 features : `Customers' Age`, `Gender`, `Annual Income` and `Spending Score`

<img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/customer_seg_data.png" alt="Dataset Summary" width="500">

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- BUSINESS PROBLEM -->
## Business Problem
* By segmenting customers into homogeneous groups, businesses aim to gain insights into their diverse needs, behaviors, and preferences, allowing for targeted marketing strategies, personalized product offerings, and improved customer satisfaction

* In the context of the mall customers dataset, the business problem being tackled through customer segmentation is to better understand the diverse shopping behaviors and preferences exhibited by different customer segments

1. **Targeted Marketing** <br> By understanding the unique needs and preferences of each customer segment, the mall can tailor its marketing strategies to effectively reach and engage with specific groups
2. **Product Assortment Planning** <br> Segmenting customers based on their spending behaviors can provide valuable insights into the types of products and services that are most appealing to each group.
3. **Customer Experience Enhancement** <br> By recognizing the distinct preferences of various customer segments, the mall can enhance the overall shopping experience by offering personalized services, targeted promotions, and loyalty programs that cater to the needs of each group
4. **Operational Efficiency** <br> Understanding customer segments can also help optimize operational processes within the mall, such as staffing levels, store layouts, and inventory management, to better meet the needs of different customer groups and improve overall efficiency.

<!-- MACHINE LEARNING SOLUTIONS -->
## Machine Learning Solutions

We use powerful unsupervised machine learining techniques like `K-Means clustering`, `DBSCAN` and `Gaussian Mixture Models` to identify the customer segments in this dataset.

### Roadmap

- [ ] Perform Exploratory Data Analysis with interactive plots to understand the data better
- [ ] Use methos like Intertia, Silhouette score and AIC, BIC curves to determine optimal number of clusters.
- [ ] Visualize the clusters for K-means, DBSCAN and GMM - understand the best performance and validate the cluster accuracy.
- [ ] Label the dataset with optimal number of clusters and develope a classification predictive model for future business strategies.

<div style="display: flex;">
  <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/newplot.png" alt="Dataset Summary" width="400">
  <img src="https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/blob/main/silhouette.png" alt="Dataset Summary" width="500", height="400">
  
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONCLUSION & FINDINGS -->
## Conclusion & Findings

* Informative findings were made from the EDA process like 50 % of the customers lie between the age gorup of 28 to 51 for Men and 29 to 49 years for women.

* With all the 3 methods of clustering i.e K-Means, DBSCAN & Gaussian Mixture Models - 2 clusters were identified.

* So the customers could be segmented into 2 catagories and now we know how their age, gender look like for those catagories through which the Mall can deduce specific target campaigns.

* Labelling of the unlabeled dataset was done, a logisctic regression model was fit with 100% accuracy. Hence the Mall can understand what cluster the customer belongs to when new unseen data comes in.


### 3D visulization with PCA and Plotly helps in demistifying clustering
At first the clustered dataset and centroid do not make sense but reducing the dimensions and then visualizing keeping 90% of the data variance same is good for understanding what's happenig under the hood!

https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/assets/130779672/3ade244e-71bf-4e66-b0fc-11afccfb6b57

<!-- CONTACT -->
## Contact

Nakul Havaldar : nakul.havaldar@gmail.com

Project Link: https://github.com/nakul3000/Customer-Segementation-with-Clustering-Classification-for-effective-marketing-decisions/tree/main

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Kaggle Community


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
