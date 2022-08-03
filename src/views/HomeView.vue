<template>
  <div class="home">

    <div class="personal-info">
      <div class="wrap-personal">
      <h1> Personal info </h1>
      <p class="para-personal"> Info about you and your preferences across Google services </p>
      </div>
    </div>

    <div class="profile-info">
      <div class="wrap-profile">
        <b-row class="row-profile">
          <b-col class="col-prof">
            <h4 class="title-prof"> Your profile info in Google services </h4>
            <p class="para-prof"> Personal info and options to manage it. You can make some of this info, 
                like your contact details, visible to others so they can reach you easily. 
                You can also see a summary of your profiles. 
            </p>
          </b-col>
          <b-col class="col-prof">
            <img src="../assets/picture1.png" alt="picture-1">
          </b-col>
        </b-row>
      </div>
    </div>

    <div class="d-flex justify-content-center">
      <div class="basic-info">
          <h4 class="title-basic">Basic Info </h4>
          <p class="para-basic"> Some info may be visible to other people using Google services.<span class="learn"> Learn more </span></p>
          <div class="wrap-table">
            <table class="table">
                <tbody>
                  <tr>
                    <td class="td-content" scope="row">Photo</td>
                    <td class="td-photo">Add photo to personalize your account</td>
                    <td class="td-image"><img src="../assets/picture2.png" alt="picture2"></td>
                  </tr>
                  <tr>
                    <td  class="td-content" scope="row">Name</td>
                    <td class="td-content2">Pringgo Waren</td>
                    <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                  </tr>
                  <tr>
                    <td class="td-content" scope="row">Birthday</td>
                    <td class="td-content2">March 6, 1997</td>
                    <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                  </tr>
                    <tr>
                      <td class="td-content" scope="row">Gender</td>
                      <td class="td-content2">Male</td>
                      <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                  </tr>
                </tbody>
            </table>
          </div>
      </div>

    </div >

    <div class="d-flex justify-content-center mt-5">
      <div class="basic-info">
          <h4 class="title-contact">Contact info </h4>
          <div class="wrap-table">
            <table class="table">
                  <tbody>
                    <tr>
                      <td class="td-content" scope="row">Email</td>
                      <td  class="td-content2">
                        <p class="content-info2" >pringgowaren@gmail.com</p>
                        <p class="content-info2">pringgo12@gmail.com</p>
                      </td>
                      <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                    </tr>
                    <tr>
                      <td class="td-content" scope="row">Phone</td>
                      <td class="td-content2">
                        <p class="content-info2">081293441505</p>
                        <p class="content-info2">085714197106</p>
                      </td>
                      <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                    </tr>
                  </tbody>
              </table>
          </div>
      </div>
    </div>

    <div class="body-card">
      <div class="wrap-card">
        <b-row class="row-card">
          <b-col class="col-card">
            <div class="card" style="width: 26rem; height: 370px; border-radius: 10px;">
              <div class="card-body">
                <h5 class="card-title">Your Profile</h5>
                <p class="card-text">See how your different profiles appear in Google services</p>
                <div class="d-flex ml-4 mt-5">
                  <div> 
                    <img style="text-align:left;" src="../assets/picture3.png" alt="picture3">
                    <p style="font-size : 14px; padding: 10px 10px 10px 10px;">Pringgo Gitoyo Waren</p>
                  </div>
                  <div> 
                    <img src="../assets/picture3.png" alt="picture3">
                    <p style="font-size : 14px; padding: 10px 10px 10px 10px;">Pringgo Waren</p>
                  </div>
                </div>
              </div>
              <div class="card-footer bg-transparent">See profiles</div>
            </div>
          </b-col>
          <b-col class="col-card mb-5">
            <div class="card" style="width: 26rem; height: 370px; border-radius: 10px;">
              <div class="card-body">
                <div class="d-flex">
                  <div>
                    <h5 class="card-title">Choose what other see</h5>
                    <p class="card-text">Decide what personal information you make visible to others when you use your main Google Account profile across Google services</p>
                  </div>
                  <div class="ml-3">
                    <img src="../assets/picture4.png" alt="picture4">
                  </div>
                </div>
              </div>
              <div class="card-footer bg-transparent">Go to about me</div>
            </div>
          </b-col>
        </b-row>
      </div>
    </div>

    <div class="profile-info mt-5">
      <div class="wrap-profile">
        <b-row class="row-profile">
          <b-col class="col-prof">
            <h4 style="text-align: left;"> Other info and preferences for Google services </h4>
            <p class="para-prof" style="text-align: left;"> Ways to verify it’s you and settings for the web</p>
          </b-col>
          <b-col class="col-prof">
            <img src="../assets/picture5.png" alt="picture-5">
          </b-col>
        </b-row>
      </div>
    </div>    

     <div class="body-card">
      <div class="wrap-card">
        <b-row class="row-card">
          <b-col class="col-card">
            <div class="card" style="width: 26rem; height: 370px; border-radius: 10px;">
              <div class="card-body">
                <h5 class="card-title" style="margin-left: 10px;">Password</h5>
                <p class="card-text" style="margin-left: 10px;">A secure password helps protect your Google Account</p>
                <div class="d-flex ml-4 mt-5" >
                  <div style="margin-left: -12px; margin-top:-20px;" > 
                    <p style="text-align:left; margin-top:-15px;">********</p>
                    <p class="last-changed" style="text-align:left; margin-top:-15px;"> Last Changed Jan 27,2020</p>
                  </div>
                </div>
              </div>
            </div>
          </b-col>
          <b-col class="col-card mb-5">
            <div class="card" style="width: 26rem; height: 370px; border-radius: 10px;">
              <div class="card-body">
                <div>
                  <div>
                    <h5 class="card-title">General preferences for the web</h5>
                    <p class="card-text">Manage settings for Google services on the web</p>
                  </div>
                  <div class="wrap-table mt-3">
                    <table class="table">
                          <tbody >
                            <tr style="border-top: none;">
                              <td class="td-content" scope="row"><img class="image-preferences" src="../assets/picture6.png" alt="picture6"></td>
                              <td  class="td-content">
                                <p class="content-title" >Language</p>
                                <p class="content-info">English (United States)</p>
                              </td>
                              <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                            </tr>
                            <tr>
                              <td class="td-content" scope="row"><img class="image-preferences2" src="../assets/picture7.png" alt="picture7"></td>
                              <td  class="td-content">
                                <p class="content-title" >Input Tools </p>
                                <p class="content-info">Type more easily in your language</p>
                              </td>
                              <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                            </tr>
                            <tr>
                              <td class="td-content" scope="row"><img class="image-preferences" src="../assets/picture8.png" alt="picture8"></td>
                              <td  class="td-content">
                                <p class="content-title" >Accessibility</p>
                                <p class="content-info">High-contrast colors OFF </p>
                              </td>
                              <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                            </tr>
                          </tbody>
                      </table>
                  </div>
                </div>
              </div>
            </div>
          </b-col>
        </b-row>
      </div>
    </div>

     <div class="d-flex justify-content-center mt-5 mb-5">
      <div class="basic-info">
          <h4 class="title-contact">Looking for something else? </h4>
          <div class="wrap-table">
            <table class="table">
                  <tbody style=" border-top-style: none;">
                    <tr class="borderless">
                      <td class="td-content1" scope="row"><img src="../assets/picture9.png" alt="picture9"></td>
                      <td  class="">
                        <p class="content-info3" >Search Google Account</p>
                      </td>
                      <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                    </tr>
                    <tr>
                      <td class="td-content1" scope="row"><img src="../assets/picture10.png" alt="picture10"></td>
                      <td class="">
                        <p class="content-info3">See Help Options</p>
                      </td>
                      <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                    </tr>
                      <tr>
                        <td class="td-content1" scope="row"><img src="../assets/picture11.png" alt="picture11"></td>
                        <td class="">
                          <p class="content-info3">Send Feedback</p>
                        </td>
                        <td class="td-image"><img src="../assets/arrow.png" alt="arrow"></td>
                    </tr>
                  </tbody>
              </table>
          </div>
      </div>
    </div>

    

  </div>
</template>


<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
}
</script>

<style scoped>

    .personal-info{
      display: flex;
      justify-content: center;
    }
    .wrap-personal{
      width: 60%;
      margin: 30px 0px 30px 0px;
    }

    .profile-info{
      display: flex;
      justify-content: center;
    }

    .title-prof{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      line-height: 2rem;
      font-size: 1.5rem;
      letter-spacing: 0;
      font-weight: 400;
      color: #202124;
      margin-left: -35px;
    }

    .para-prof{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01785714em;
      line-height: 1.25rem;
      hyphens: auto;
      word-break: break-word;
      word-wrap: break-word;
      color: #5f6368;
      margin-top: 12px;
    }

    .wrap-profile{
      width: 60%;
    }

    .basic-info{
      width: 60%;
      height: auto;
      border-style: solid;
      border-color: lightgray;
      border-radius: 15px;
      border-width: 1px;
    }

    .learn{
      color: rgb(22, 22, 245);
    }

    .title-basic{
      text-align: left;
      padding: 20px 30px 0px 30px;
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 1rem;
      font-weight: 500;
      letter-spacing: 0.009375em;
      line-height: 1.5rem;
      color: #202124;
    }

    .wrap-table{
      display: flex;
      justify-content: end;
    }

    .table{
      width: 96%;
    }

    .td-content{
      text-align: left;
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.75rem;
      font-weight: 500;
      letter-spacing: 0.04166667em;
      line-height: 1rem;
      color: #5f6368;
      padding-right: 50px;
    }

    .td-content1{
       text-align: left;
       padding-right:10px;
    }

    .td-content2{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01785714em;
      line-height: 1.25rem;
      text-align: left;
    }

    .td-image{
      text-align: right;
    }

    .para-basic{
      text-align: left;
      padding: 0px 30px 20px 30px;
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01428571em;
      line-height: 1.25rem;
      color: #5f6368;
    }

    .content-table{
      background-color: red;
      width: 20%;
      height: 50px;
      text-align: left;
    }

    .td-photo{
      text-align: left;
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01428571em;
      line-height: 1.25rem;
      color: #5f6368;
      width: 100%;
    }

    .content-contact{
      color: black;
      text-align: left;
    }

    .title-contact{
      text-align: left;
      padding: 20px 30px 20px 30px;
    }

    .content-title{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01785714em;
      line-height: 1.25rem;
      hyphens: auto;
      word-break: break-word;
      word-wrap: break-word;
      color: #202124;
      margin: 0;
      padding: 0;
      width: 100%;
    }

    .content-info3{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01785714em;
      line-height: 1.25rem;
      color: #202124;
      text-align: left;
      padding-left: -50px;
    }

    .content-info2{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01785714em;
      line-height: 1.25rem;
      hyphens: auto;
      word-break: break-word;
      word-wrap: break-word;
      color: #202124;
    }

    .content-info{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      height: auto;
      color: #5f6368;
    }

    .body-card{
      margin-top:30px;
      display: flex;
      justify-content: center;
    }

    .wrap-card{
      width: 60%;
    }

    .last-changed{
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01428571em;
      line-height: 1.25rem;
      hyphens: auto;
      word-break: break-word;
      word-wrap: break-word;
      color: #5f6368;
      width: 100%;
    }

    .card-title{
      text-align: left;
    }

    .card-text{
      text-align: left;
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 400;
      letter-spacing: 0.01428571em;
      line-height: 1.25rem;
      color: #5f6368;
    }

    .card-footer{
      text-align: left;
      color: #1a73e8;
      font-family: "Google Sans",Roboto,Arial,sans-serif;
      font-size: 0.875rem;
      font-weight: 500;
      line-height: 1.25rem;
    }

    .image-preferences{
      margin-top:7px;
    }

    .image-preferences2{
      margin-top:20px;
    }

</style>
