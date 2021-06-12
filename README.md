<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="Resources/hotel.png" type="image/x-icon">
    <link rel="stylesheet" href="hotel.css">
    <title>Hotel Template</title>
</head>

<body>
    <header>
        <nav>
            <a href="#" class="btn specialbtn">Logo</a>
            <a href="#Rooms" class="btn">Rooms</a>
            <a href="#About" class="btn">About</a>
            <a href="#Contact" class="btn">Contact</a>
            <a href="login.html" class="btn">Login</a>
            <a href="register.html" class="btn">Register</a>
        </nav>
    </header>
    <div class="MainShow">
        <img class="imgShow" src="./Resources/hotel.jpg" alt="Image hotel">
    </div>
    <div class="Check">
        <div class="ChkHead">
            <h2>Bedo Hotels</h2>

        </div>
        <div class="ChkBody">
            <form action="#">
                <div>
                    <div class="shIn">
                        <label for="ChIn">Check In</label><br>
                        <input placeholder="DD MM YYYY" type="text" class="shin" name="ChIn">
                    </div>
                    <div class="shIn">
                        <label for="ChOut">Check Out</label><br>
                        <input placeholder="DD MM YYYY" type="text" class="shin" name="ChOut">
                    </div>
                </div>
                <div>
                    <div class="shIn">
                        <label for="Adult">Adult</label><br>
                        <input placeholder="1" type="number" class="shin" name="Adult">
                    </div>
                    <div class="shIn">
                        <label for="Kids">Kids</label><br>
                        <input placeholder="0" type="number" class="shin" name="Kids">
                    </div>
                </div>
                <button class="btnShow shin" type="submit">Search Availabilty</button>
            </form>

        </div>
    </div>
    <div class="Content">
        <div class="Rooms" id="Rooms">
            <h3>Rooms</h3>
            <p>Make yourself at home is our slogan. We offer the best beds in the industry. Sleep well and rest well.
            </p>
        </div>
        <div class="book">
            <form action="#">
                <div class="row">
                    <div class="shRooms">
                        <label for="ChIn">Check In</label><br>
                        <input placeholder="DD MM YYYY" type="text" class="shin" name="ChIn">
                    </div>
                    <div class="shRooms">
                        <label for="ChOut">Check Out</label><br>
                        <input placeholder="DD MM YYYY" type="text" class="shin" name="ChOut">
                    </div>
                </div>
                <div class="row">
                    <div class="shRooms">
                        <label for="Adult">Adult</label><br>
                        <input placeholder="1" type="number" class="shin" name="Adult">
                    </div>
                    <div class="shRooms">
                        <label for="Kids">Kids</label><br>
                        <input placeholder="0" type="number" class="shin" name="Kids">
                    </div>
                </div>
                <div class="row divbtn">
                    <button class="btnSearch shRooms shin" type="submit">Search</button>
                </div>
            </form>
        </div>
        <div class="roomstype">
            <div class="rooms">
                <img class="roomsimg" src="Resources/room_single.jpg" alt="NorWay">
                <div class="info">
                    <h3>Single Room</h3>
                    <h6 class="opac">From $99</h6>
                    <p>Single Bed</p>
                    <p>15m <sup>2</sup></p>
                    <button class="ChooseRoom">Choose Room</button>
                </div>
            </div>
            <div class="rooms">
                <img class="roomsimg" src="Resources/room_double.jpg" alt="NorWay">
                <div class="info">
                    <h3>Double Room</h3>
                    <h6 class="opac">From $149</h6>
                    <p>Queen-size bed</p>
                    <p>25m <sup>2</sup></p>
                    <button class="ChooseRoom">Choose Room</button>
                </div>
            </div>
            <div class="rooms">
                <img class="roomsimg" src="Resources/room_deluxe.jpg" alt="NorWay">
                <div class="info">
                    <h3>Deluxe Room</h3>
                    <h6 class="opac">From $199</h6>
                    <p>King-size bed</p>
                    <p>40m <sup>2</sup></p>
                    <button class="ChooseRoom">Choose Room</button>
                </div>
            </div>
        </div>
        <div style="padding: 0.01em 16px;" id="About">
            <div class="about">
                <h3>About</h3>
                <h6 style="font-size: 16px;">Our hotel is one of a kind. It is truely amazing. Lorem ipsum dolor sit
                    amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
                    commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
                    fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia
                    deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod
                    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</h6>
            </div>
            <div class="aboutimg">
                <img width="100%" src="Resources/map.jpg" alt="map">
            </div>
        </div>
        <div style="clear: both;"></div>
        <div class="contactinfo">
            <p class="infoc"> 423 Some adr, Chicago, US</p>
            <p class="infoc">Phone: +00 151515</p>
            <p class="infoc">Email: mail@mail.com</p>
        </div>
        <div style="margin:10px; padding: 50px 16px; background-color: red; text-align: center;">
            <h6 style="font-size: 16px;"> On demand, we can offer playstation, babycall, children care, dog equipment,
                etc.</h6>
        </div>
        <div style="margin: 10px; padding: 25px 1px;">
            <h3>Our Hotels</h3>
            <h6 style="font-size: 16px;">You can find our hotels anywhere in the world:</h6>
        </div>
        <div>
            <div class="half">
                <img src="Resources/cinqueterre.jpg" alt="photo">
                <span class="title">Cinqueterre</span>
            </div>
            <div class="half">
                <div class="quarter">
                    <img src="Resources/newyork2.jpg" alt="newyork">
                    <span class="title">New York</span>
                </div>
                <div class="quarter">
                    <img src="Resources/sanfran.jpg" alt="san">
                    <span class="title">San Francisco</span>
                </div>
                <div class="quarter">
                    <img src="Resources/pisa.jpg" alt="piza">
                    <span class="title">Pizaa Tower</span>
                </div>
                <div class="quarter">
                    <img src="Resources/paris.jpg" alt="paris">
                    <span class="title">Paris</span>
                </div>
            </div>
        </div>
        <div class="offers">
            <h2>Get the best offers first! </h2>
            <p style="margin-bottom: 10px;">Join our newsletter. </p>
            <label for="email">E-mail</label>
            <br>
            <input type="email" placeholder="Your Email Address">
            <button class="subscribe">Subscribe</button>
        </div>
        <div class="c" id="Contact">
            <h2>Contact</h2>
            <p>If you have any questions, do not hesitate to ask them.</p><br>
            <p> Chicago US </p>
            <p>Phone: +00 151515</p>
            <p>Email: mail@mail.com</p>
            <form action="#">
                <input class="msgname" type="text" placeholder="Name" required >
                <input type="email" placeholder="Email" required>
                <input class="msgname" type="text" placeholder="Message" required>
                <button class="btnsend" type="submit">SEND MESSAGE</button>
            </form>
                
        </div>
    </div>
    <footer>
        <p>
            Powered By <a href="www.linkedin.com/abdelkadermahmooud">Abdelkader Mahmooud</a>

        </p>
    </footer>

</body>

</html>
