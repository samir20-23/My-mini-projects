###imag on text###
h1{
font-size: 15vw;
background-image: url(soli.jpg);
background-size: cover;
background-clip: text;
-webkit-background-clip: text;
color:transparent;

    }
    ### imag disayn####

    img{
   
    transform: rotate(-30deg); /// dwran img
    transform: scaleX(6);  ///tmdid mn jhat X
    transform: scaleY(12);  ////tmdid mn jhat y
     transform: scale(12);  ////tmdid mn jhatat klha
    transform: rotateX(181deg);  /// 9lb 3aks img 
    transform: translate(100px,100px);  /// park f paj
  transform: skewY(15deg); // jbd img mn jnab
 
 }


////imag
<img class="img1" src="https://media.istockphoto.com/id/1449784915/photo/digital-brain.jpg?s=612x612&w=0&k=20&c=3IbEhLnYth164iPGI026GWiXcedswAJE99VHSn-pqkU=" alt="img" width="311px">
    <img class="img2" src="https://images.unsplash.com/photo-1508739773434-c26b3d09e071?auto=format&fit=crop&q=60&w=400&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjZ8fHdhbGxwYXBlciUyMDRrfGVufDB8fDB8fHww" alt="img" width="311px">
    <img class="img4" src="https://images.unsplash.com/photo-1617791160536-598cf32026fb?auto=format&fit=crop&q=60&w=400&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTZ8fHdhbGxwYXBlciUyMDRrfGVufDB8fDB8fHww" alt="img" width="311px">
    <img class="img5" src="https://images.unsplash.com/photo-1618005198919-d3d4b5a92ead?auto=format&fit=crop&q=60&w=400&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MzB8fHdhbGxwYXBlciUyMDRrfGVufDB8fDB8fHww" alt="img" width="311px">
        <img class="img6" src="https://media.istockphoto.com/id/1401980646/photo/3d-rendered-classic-sculpture-metaverse-avatar-with-network-of-low-poly-glowing-purple-lines.jpg?s=612x612&w=0&k=20&c=SyPEypDcGl9021jj7pP0GW3T_Y7FNa_0yEt9KAak4Gk=" alt="img" width="311px">

        #####################thrik#######################

@keyframes rotateImage {                     /*smi hd 3mliya ay ism */
  0% {                                        /* bdaya thwl*/
    transform:  translateX(0);                     /* */
  }
  100% {                                         /* nihaya thwl*/
    transform: translate(300px,300px) ;                    /* hawl : ila hada lmw93 300X 300Y*/
  }
}
        ////////////hd str f lmotaba9 3alyh//////////
animation: rotateImage 3s linear infinite;
    animation-direction: alternate-reverse; /*ithaw bsalaasa*/

    ############thrik button########
    @keyframes rotateImage {
  0% {
    transform:  tr(0);
  }
  100% {
    transform: rotate(-20deg) ;
  }
}


.button {
  background-color: #007bff; /* Background color */
  color: #fff; /* Text color */
  border: none; /* Remove the border */
  padding: 10px 20px; /* Add padding to the button */
  border-radius: 5px; /* Add rounded corners */
  cursor: pointer; /* Change cursor to a hand on hover */
}

.button:hover {animation: rotateImage 0.1s linear infinite;
    animation-direction: alternate-reverse;
  background-color: #0056b3; /* Change background color on hover */
}
#################################
