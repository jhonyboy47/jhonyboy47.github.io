1) The following lines make the links display horizontally
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

2) This is the line that makes the hamburger menu appear
      <i class="fa fa-bars"></i>

3) When the screen size is smaller than 600px  .topnav a:not(:first-child) is used to target all other links besides home.
   These anchors are then hidden from the screen when the screen width is less than 600px.
