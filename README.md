.dropdown{
    display: inline-block; 
    position: relative;
}
.dropdown-content{
    display: none;
    position: absolute;
    min-width: 160px;
    z-index: 1;
    top: 103%;
    /* top: 105%; */
    left: 0;
}
.dropdown-content a {
    background: red;
    color: black;
    text-decoration: none;
    display: block;
    padding: 12px 16px;
    
}
.dropdown:hover .dropdown-content {
    display: block;
  }
