<template>
  <div>
   <div class="icon_div">
    <div id="icon1"><i class="bi bi-house-gear"></i></div>
    <nav class="navbar navbar-expand-lg navbar-light " id="nav">
  <div class="container-fluid" >
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo01" >
      <a class="navbar-brand" href="#">Home</a>
      <ul class="navbar-nav me-auto mb-2 mb-lg-0" id="container-div">
        <li class="nav-item item_navbar">
          <a class="nav-link active" aria-current="page" href="#">about</a>
        </li>
        <li class="nav-item item_navbar">
          <a class="nav-link" href="#">service</a>
        </li>
        <li class="nav-item item_navbar">
          <a class="nav-link" href="#" tabindex="-1" aria-disabled="true">contact</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
   </div>
<div>
    <div class="wrapper">
        <form action="#" class="wrapper__form">
            <h1>Sign Up</h1>
            <div class="border"></div>
            <div class="wrapper__flex">
                <div class="wrapper__item">
                    <label for="fname">Full Name</label>
                    <input type="text" id="fname" placeholder="Enter your name" required>
 
                    <label for="email">Email</label>
                    <input type="text" id="email" placeholder="Enter your email" required>
                    
                    <label for="password">Password</label>
                    <input type="password" id="password" placeholder="Enter your password" required>
                    
                 </div>
                 <div class="wrapper__item">
                     <label for="username">Username</label>
                    <input type="text" id="username" placeholder="Enter your username" required>
                    
                    <label for="number">Phone Number</label>
                    <input type="number" id="number" placeholder="Enter your number" required>
                    
                    <label for="password">Confirm Password</label>
                    <input type="password" id="password" placeholder="Confirm your password" required>
                    
                 </div>
            </div>
            <div class="wrapper__radio">
                <h2>Gender</h2>
                <input type="radio" id="male" name="group1" required>
                <label for="male">Male</label>
                <input type="radio" id="fmale" name="group1" required>
                <label for="fmale">Female</label>
                <input type="radio" id="notSay" name="group1" required>
                <label for="notSay">Prefer not to say</label>
                <button type="submit">Sign Up</button>
            </div>
        </form>
    </div>
   </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css");
  body{
    margin: 0;
    padding: 0;
    background-color: rgba(43, 43, 222, 0.55);
}
h1, h2, h3, h4, h5, h6{
    margin: 0;
    padding: 0;
}
#nav{
  width:75pc;
}
#container-div{
  margin-left: 20pc;
}
.item_navbar{
  margin-left: 3pc;
}
.icon_div{
  display: flex;
  align-content: center;
}
#icon1{
  margin-top: 1pc;
  width: 5pc;
  font-size: 25px;
}
.wrapper{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
 .wrapper__form{
    width: 500px;
    background-color: #fff;
    border-radius: 5px;
    padding: 20px;
} 
  .wrapper__form label{
      color: rgba(0, 0, 0, 0.7);
  }
  .border{
      width: 32px;
      border-bottom: 3px solid rgba(43, 43, 222, 0.55);
      border-radius: 10px;
  }
  .wrapper__flex{
      display: flex;
      justify-content: space-between;
  }
  .wrapper__item label{
      display: block;
      margin-bottom: 5px;
      margin-top: 15px;
      font-weight: bold;
  }
  .wrapper__item input{
      width: 200px;
      padding: 7px 10px;
      border: 1px solid rgba(196, 196, 195, 0.55);
  }
  .wrapper__radio h2{
      margin-top: 25px;
      margin-bottom: 15px;
      color: rgba(0, 0, 0, 0.7);
  }
  .wrapper__radio label{
      margin-right: 25px;
      font-weight: bold;
  }
  .wrapper__radio label:last-child{
      margin-right: 0;
  }
  .wrapper__radio button{
      margin: 30px 0;
      bottom: none;
      background-color: rgb(43, 43, 222, 0.55);
      color: #fff;
      width: 100%;
      padding: 10px 0;
      border-radius: 6px;
      font-weight: bold;
      border: none;
  }
</style>