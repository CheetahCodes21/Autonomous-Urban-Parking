# Autonomous Urban Parking - <i>PARKEASE</i>

<br/>
<p align="center">
  <a href="https://github.com/CheetahCodes21/Autonomous-Urban-Parking-/blob/main/images/company_logo.png">
    <img src="images/company_logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">PARKEASE</h3>

  <p align="center">
    "Park with ease, pay within a breeze - your hassle-free parking solution is here with PARKEASE!"
    <br/>
    <br/>
    <a href="https://github.com/CheetahCodes21/Autonomous-Urban-Parking-/blob/main/PARKEASE%20DOCUMENTATION/PARKEASE%20DOCUMENTATION.pdf"><strong>Project Documentation</strong></a>
    <br/>
    <br/>
    <a href="https://parkease.vercel.app">PARKEASE</a>
    .
    <a href="https://drive.google.com/file/d/1k35T2plLICuuwJIJoQ_r9BUdfotTNSuZ/view?usp=drive_link">View Demo</a>
    .
    <a href="https://github.com/CheetahCodes21/Autonomous-Urban-Parking/issues">Issues</a>
  </p>
</p>



## Table Of Contents
* [About the Project](#about-the-project)
* [Methodology](#Methodology)
* [License](#license)

## About The Project
Introducing PARKEASE, the revolutionary concept designed to streamline parking with zero human intervention. Say goodbye to the hassle of searching for parking spots and dealing with attendants. PARKEASE leverages cutting-edge technology to automate the entire parking process, ensuring a seamless experience for users.

## Methodology



1. **User Registration:**
   - Users visit [parkease.vercel.app](https://parkease.vercel.app) to register by providing their vehicle number, name, and basic details.
   - Upon registration, a digital wallet is created for the user, allowing them to add money using preferred payment methods.

2. **Parking Entry:**
   - When a vehicle enters the parking lot, sensors detect its presence and trigger the camera.
   - The camera captures the vehicle number plate, which is processed using Optical Character Recognition (OCR) or Tesseract.
   - The extracted number along with the timestamp is sent to the database (Firebase), and a parking slot is assigned.
   - For registered users, the system checks their wallet balance. A minimum balance is required for parking.

3. **Parking Duration:**
   - The system records the entry time and calculates the duration of parking based on the entry and exit times.

4. **Exit Process:**
   - When the vehicle exits, the exit time is recorded.
   - For registered users, the system automatically deducts the parking fee from their wallet if they have a sufficient balance.
   - Guest users receive a dynamic QR code containing the bill amount, which they pay upon exit.

5. **Billing:**
   - The billing system calculates the parking fee based on the time parked, with a standard rate per hour.

## License
Distributed under the MIT License. See [LICENSE](https://github.com/CheetahCodes21/Autonomous-Urban-Parking-/blob/main/LICENSE.md) for more information.
