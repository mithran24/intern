# intern
*{
    /* margin: 0;
    padding: 0; */
    /* box-sizing: border-box; */
    list-style: none;
    /* font-family: 'Josefin Sans', sans-serif; */
  }
.wrapper{
    position: absolute;
    margin-top: 200px;
    margin-left: 250px;
    /* transform: translate(-50%,-50%); */
    width: 800px;
    height: 50px;
    /* padding: 25px 35px; */
    background: black;
    /* border-radius: 50px; */
    box-shadow: 0 0 5px rgba(0,0,0,0.125);
  }
  
.wrapper ul{
    display: flex;
    text-align: center;
    margin-top: 5px;
    margin-left: -25px;
}
  
.wrapper ul li{
    width: 40px;
    height: 40px;
    line-height: 40px;
    margin: 1px 3px;
    background: black;
    color: #000;
    box-shadow: 0 0 5px rgba(0,0,0,0.5);
    cursor: pointer;
    border-radius: 50%;
  }

.wrapper ul li a{
    text-decoration: none;
    border-radius: 50%;
    color: whitesmoke;
}
  

.wrapper ul li:hover,
.wrapper ul li.active{
    background: #fd4141;
    color: #fff;
  }

#prev-page{
    transform: rotate(180deg);
    text-decoration: none;
}

.wrapper ul span{
    margin-top: 9px;
    margin-left: 180px;
    color: white;
}
