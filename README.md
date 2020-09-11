<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://iotkiit.in/hacktober/static/media/Icon.08e8a3d5.png" alt="logo"></a>
</p>

<h3 align="center">OPEN SOURCE FTW 2020</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Platform](https://img.shields.io/badge/platform-heroku-lightgrey)]()
[![GitHub Issues](https://img.shields.io/github/issues/iot-lab-kiit/contributorsPage)](https://github.com/iot-lab-kiit/contributorsPage/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/iot-lab-kiit/contributorsPage)](https://github.com/iot-lab-kiit/contributorsPage/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">An HTML delivered via express to show contributors for the Open Source FTW 2020/ Hacktober 2020 Pull Requests.
    <br> 
</p>


## 🎈 Creating a pull request <a name = "usage"></a>

To create a pull request to show your name on the website, first find the file:

```
/public/index.html
```

Please be **careful** while editing the file.

### Find the following comments:

```
<!-- one profile block goes here-->
        <div class="profile-box">
        <img src="%image url%" alt="profile pic">
        <h3>Your Name</h3>
        <h4><a href="https://www.github.com/%username%" target="_blank">Your Github Username</a></h4>
      </div>
<!-- profile block ends here-->
```

**Replace the fields with your information:**
- Go to your Github, right-click on your Github profile and click **Copy image address**. This will be 
> img src = "url you just copied"

- Add your username in place of %username% in 
> href = "https://www.github.com/%username%" 

- Add your name and github username in &#60;h3&#62; and &#60;h4&#62; tags respectively. 


### Example:

```
<!-- one profile block goes here-->
        <div class="profile-box">
        <img src="https://avatars3.githubusercontent.com/u/55389335?s=460&u=25493fd6332774036935e723c524c4ccbc0e1d0c&v=4" alt="profile pic">
        <h3>Sahil</h3>
        <h4><a href="https://www.github.com/SahilKr24" target="_blank">SahilKr24</a></h4>
      </div>
<!-- profile block ends here-->
```

## 🏁 Final Steps <a name = "getting_started"></a>

**Place this entire code on the line empty line above**
> &#60;!-- insert your block of code here and please leave 2 lines empty above for others to navigate easily --&#62;

Also follow the instruction as written in the line of comment.

Save the file and create a PR, sit back and wait until we approve your PR, ofc, if it fits the instructions.

**Check out if your name shows up at**

**[HF 2K20 Contributors](https://osftw2020.herokuapp.com/)**
### Prerequisites


## ✍️ Authors <a name = "authors"></a>

- [@SahilKr24](https://github.com/SahilKr24)


