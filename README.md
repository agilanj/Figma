# Ex09 Event Registration Web Application
# Date: 14-12-2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
~~~
<html>
<style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  color: rgba(255, 255, 255, 1);
  white-space: nowrap;
  margin: 0 auto;
  padding: 49px 24px 227px;
  font: 400 24px Inder, sans-serif;
}

.hero-image {
  aspect-ratio: 4.61;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-image {
  aspect-ratio: 0.91;
  object-fit: contain;
  object-position: center;
  width: 172px;
  margin-top: 97px;
  max-width: 100%;
}

.registration-icon {
  aspect-ratio: 2.58;
  object-fit: contain;
  object-position: center;
  width: 116px;
  border-radius: 5px;
  margin-top: 74px;
  max-width: 100%;
}

.register-button {
  background-color: rgba(54, 50, 120, 1);
  margin-top: 29px;
  width: 116px;
  max-width: 100%;
  overflow: hidden;
  padding: 9px 10px 19px;
  border: none;
  cursor: pointer;
  color: inherit;
  font: inherit;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/fba26f2227d33f02ab84d07e3ce0ab62c86831ce159ca114d6d6d12e8c545255?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
    class="hero-image"
    alt="Registration hero banner"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/8d2e978f97a8e0506e5f3791a376903cffbb9382cd6a7252cd9f9e5d41aa012c?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
    class="logo-image"
    alt="Company logo"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/baef0d4193391a21f3204e41c7312c45978bef37f555b0c37105f575ac1b3778?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
    class="registration-icon"
    alt="Registration process icon"
  />
  <button class="register-button" tabindex="0">REGISTER</button>
</div>
</html>
~~~
~~~
<html>
<style>
.login-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  margin: 0 auto;
  padding: 43px 9px 225px;
}

.logo-image {
  aspect-ratio: 4.98;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.form-wrapper {
  display: flex;
  margin-top: 268px;
  width: 100%;
  max-width: 343px;
  gap: 20px;
}

.form-labels {
  color: rgba(255, 255, 255, 1);
  align-self: start;
  width: 100%;
  font: 400 24px Inder, sans-serif;
}

.input-container {
  display: flex;
  flex-direction: column;
}

.username-input {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  height: 29px;
}

.password-input {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  margin-top: 31px;
  height: 31px;
}

.login-button {
  background-color: rgba(56, 64, 140, 1);
  margin-top: 81px;
  width: 174px;
  max-width: 100%;
  overflow: hidden;
  color: rgba(255, 249, 249, 1);
  white-space: nowrap;
  padding: 8px 55px 22px;
  font: 400 24px Inder, sans-serif;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="login-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/e49f52b7296805c0dc3685bc690084c5a9090dc42a3745a75fcd0ffed83bc8ec?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
    class="logo-image"
    alt="Company Logo"
  />
  <form class="form-wrapper">
    <div class="form-labels">
      <label for="username">USERNAME :</label>
      <br />
      <br />
      <label for="password">PASSWORD :</label>
    </div>
    <div class="input-container">
      <input type="text" id="username" class="username-input" aria-label="Username input field" />
      <input type="password" id="password" class="password-input" aria-label="Password input field" />
    </div>
  </form>
  <button type="submit" class="login-button">LOGIN</button>
</div>
</html>
~~~
~~~
<html>
<style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  margin: 0 auto;
  padding: 54px 10px 188px;
}

.logo-image {
  aspect-ratio: 4.98;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.form-wrapper {
  display: flex;
  margin-top: 85px;
  width: 100%;
  max-width: 394px;
  gap: 17px;
}

.form-labels {
  color: rgba(255, 251, 251, 1);
  align-self: start;
  width: 100%;
  font: 400 24px Inder, sans-serif;
}

.input-container {
  display: flex;
  flex-direction: column;
}

.text-input {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  width: 200px;
  height: 33px;
  margin-top: 29px;
  border: none;
  padding: 5px;
}

.text-input:first-child {
  margin-top: 0;
}

.otp-container {
  align-self: start;
  display: flex;
  margin-top: 61px;
  gap: 18px;
}

.otp-input {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  width: 38px;
  height: 33px;
  border: none;
  text-align: center;
}

.register-button {
  background-color: rgba(22, 61, 129, 1);
  margin-top: 75px;
  width: 174px;
  max-width: 100%;
  overflow: hidden;
  color: rgba(255, 255, 255, 1);
  white-space: nowrap;
  padding: 8px 35px 22px;
  font: 400 24px Inder, sans-serif;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/e49f52b7296805c0dc3685bc690084c5a9090dc42a3745a75fcd0ffed83bc8ec?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
    class="logo-image"
    alt="Company Logo"
  />
  <form class="form-wrapper">
    <div class="form-labels">
      NAME :
      <br />
      <br />
      REG NO :
      <br />
      <br />
      EMAIL :
      <br />
      <br />
      MOB NUMBER :
      <br />
      <br />
      <br />
      OTP :
      <br />
    </div>
    <div class="input-container">
      <label for="name" class="visually-hidden">Name</label>
      <input type="text" id="name" class="text-input" aria-label="Name input" />
      
      <label for="regno" class="visually-hidden">Registration Number</label>
      <input type="text" id="regno" class="text-input" aria-label="Registration number input" />
      
      <label for="email" class="visually-hidden">Email</label>
      <input type="email" id="email" class="text-input" aria-label="Email input" />
      
      <label for="mobile" class="visually-hidden">Mobile Number</label>
      <input type="tel" id="mobile" class="text-input" aria-label="Mobile number input" />
      
      <div class="otp-container" role="group" aria-label="OTP input">
        <input type="text" class="otp-input" maxlength="1" aria-label="OTP digit 1" />
        <input type="text" class="otp-input" maxlength="1" aria-label="OTP digit 2" />
        <input type="text" class="otp-input" maxlength="1" aria-label="OTP digit 3" />
      </div>
    </div>
  </form>
  <button type="submit" class="register-button">
    REGISTER
  </button>
</div>
</html>
~~~
~~~
<html>
<style>
.activities-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  padding: 50px 17px 167px;
}

.logo-image {
  aspect-ratio: 4.78;
  object-fit: contain;
  object-position: center;
  width: 407px;
}

.activities-wrapper {
  align-self: center;
  display: flex;
  margin-top: 97px;
  width: 100%;
  max-width: 349px;
  gap: 34px;
}

.icon-list {
  display: flex;
  flex-direction: column;
}

.activity-icon {
  aspect-ratio: 1;
  object-fit: contain;
  object-position: center;
  width: 26px;
}

.icon-spacing-1 { margin-top: 28px; }
.icon-spacing-2 { margin-top: 38px; }
.icon-spacing-3 { margin-top: 32px; }
.icon-spacing-4 { margin-top: 40px; }

.activity-list {
  color: rgba(255, 255, 255, 1);
  flex-grow: 1;
  width: 284px;
  flex-basis: auto;
  font: 400 24px Inder, sans-serif;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="activities-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/TEMP/1d17331aff18e7de36f2d1a8d635ef0361565592d19a3caa20402d8ae38c857e?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
    class="logo-image"
    alt="Activities section logo"
  />
  <div class="activities-wrapper">
    <div class="icon-list">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon"
        alt="Maths quiz icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-1"
        alt="3D printing icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-1"
        alt="Web development icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-2"
        alt="Painting icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-2"
        alt="Clay pot making icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-3"
        alt="Puzzle solving icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-1"
        alt="Chess icon"
      />
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/ac007deb73456d05929160d82b9509b008f953b812419ae1168d0cc37b26fe42?placeholderIfAbsent=true&apiKey=fc737d6485fb4ae2aa9489e6934c19b0"
        class="activity-icon icon-spacing-4"
        alt="Problem solving icon"
      />
    </div>
    <div class="activity-list" role="list">
      MATHS QUIZ
      <br />
      <br />
      3D PRINTING
      <br />
      <br />
      WEB PAGE DEVELOPMENT
      <br />
      <br />
      PAINTING
      <br />
      <br />
      CLAY POT MAKING
      <br />
      <br />
      PUZZLE SOLVING
      <br />
      <br />
      CHESS
      <br />
      <br />
      PROBLEM SOLVING
    </div>
  </div>
</div>
</html>
~~~
# OUTPUT:
![Screenshot (108)](https://github.com/user-attachments/assets/a2f9d148-8c3f-4d9c-90fa-9b8789c5aff6)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
