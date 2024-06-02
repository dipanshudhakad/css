body{
    font-family:  sans-serif;
    background-color: black;
    color: white;
    overflow: hidden;
    margin: 0;
}
.main{
    display: flex;
    height: 100vh;
}
.sidebar{ background-color:black;
    width: 340px;
    border-radius: 1rem;
    margin-right: 0.5rem;

}
.main_contact{
    background-color:#121212;;
    flex: 1;
    border-radius: 1rem;
    overflow: auto;
    padding: 0 1.5rem 0 1.5rem;
}
.music_player{
     background-color: black;
     position: fixed;
     height: 72px;
     bottom: 0;
     width: 100%;
}
a{
    text-decoration: none;
    color: white  ;

}
.nav{
    background-color: black;
    display: flex;
    border-radius: 1rem;
    flex-direction: column;
    justify-content: center;
    height: 100px;
    padding: 0.5rem 0.75rem;
}
.nav_option{
    line-height: 2.5rem;
    opacity: 0.7rem;
    padding: 0.5rem 0.75rem;
}
.nav_option:hover{
    opacity: 1;
}
.nav_option a{
    font-size: 1rem;
    margin-left: 1rem;
}
.nav_option i{
     font-size: 1.25rem;
}
.library{
    background-color: #121212;
    border-radius: 1rem;
    height: 100%;
    margin-top: 0.5rem;
    padding: 0.5rem 0.75rem;


}
.options{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.lib_option img{
    height: 1.25rem;
    width: 1.25rem;
}
.icon{
    font-size: 1.25rem;
    display: flex;

}
.icon i{
    opacity: 0.7rem;
    margin-right: 1rem;
    

}
.icon i:hover{
    opacity: 1rem;
}
.box{
    background-color: #232323;
    height: 8rem;
    border-radius: 0.75rem;
    margin: 0.5rem 0 0.5rem 0;
    padding: 1rem 1.25rem;
}
.box-p1{
    font-size: 1rem;
    font-weight: 500;

}
box-p2{
font-size: 0.75rem;
opacity: 0.9;
}
.badge{
    background-color: #fff;
    border: none;
    border-radius: 100px;
    padding: 0.25rem 1 rem;
    font-weight: 700;
    margin-top: 0.5rem;
    height: 2rem;
    width: fit-content;
}
.dark_badge{
    background-color: black;
    color: white;
}

.sticky_nav{
    background-color: #121212;
    position: sticky;
    top: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0 1rem;
    z-index:10;
}
.stikcy_nav_icon{margin-left: 0.75rem;
   }
.stikcy_nav_options{
    display: flex;
    justify-content: center;
    align-items: center;

}
.nav_item{
    margin-right: 1rem;
}
@media(max-width:1000px){
    .hide{
        display: none;
    }
}
.card {
    background-color: #232323;
    width: 150px;
    border-radius: 0.5rem ;
    padding: 1rem;
    margin-left:1.5rem ;
    margin-top: 1rem;
}
.card_container{
    display: flex;
    flex-wrap: wrap;
}
.card_img{
    width: 100%;
    border-radius: 0.5rem;
}
.card_title{
    font-weight: 600;
}
.card_info{
    font-size: 0.85rem;
    opacity: 0.8;
}
.footer{
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;

}
.line{
   width: 90%;
   height: 30%; 
   border-top: 2px soild white;
   opacity: 0.4;
}
.musicplayer{
    display: flex;
}
.album{
    width: 25%;
}
.player{
    width: 50%;
}
.countrols{
    width: 25;
}


