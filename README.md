
.footer-social {
    display: flex;
    justify-content: center;
}

.footer-social i {
    margin: 0 0.625rem;
    font-size: 1.5rem;
    color: var(--color-nav);
    cursor: pointer;
}

.footer-social i:hover {
    color: #e50c39;
}

.copyright {
    text-align: center;
    font-size: 0.9rem;
    color: #666;
    padding-top: 1.25rem;
    /*padding: 20px 0 0 0;*/
} 

@media(max-width:1024px){
    /* Tablet (≤ 1024px): 2 columnas */
#header-container{
    padding: 0.625rem 0.938rem;
}
#header-container img{
    width: 100px ;
    height: 100px;
    margin-bottom:  0.625rem;
 }

 .gallery{
    flex-direction:row;
    margin-top: 3.75rem;
 }
.gallery li{
     width: calc(100% / 2);
     justify-content: center;
     }
}

/* Mobile (≤ 768px): 1 columna */
@media(max-width: 768px){

#header-container {
   padding: 0.625rem 0.938rem;
  }

nav ul{
    display:flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 0;
}

nav ul li {
   display: block;
   width: 100%;
   text-align: center;
}
 nav ul li a {
    display: block;
    padding: 10px 15px;
    border-bottom: 1px solid #f0f0f0;
  }

.brand-header{

    font-size: 2.2rem;
    padding-top: 1rem;
    letter-spacing: 1px;

}

 main h2 {
    font-size: 1.5rem;
    letter-spacing: 1px;
    margin: 1rem 0;
  }

.gallery {
    flex-direction: column;
    margin-top: 1.25rem;
  }

  .gallery li {
    width: 100%;
    padding: 0.5rem 0.625rem;
  }

   .gallery li .box p {
    font-size: 1.5rem;
  }
  
  .gallery li .box .button {
    font-size: 1rem;
    padding: 10px;
  }
  
   .footer-nav ul {
    flex-direction: column;
    align-items: center;
    gap: 0.625rem;
  }
  
  
  .footer-nav ul li {
    margin: 0;
  }
  
  .footer-social i {
    font-size: 1.8rem;
    margin: 0 0.75rem;
  }
  


}

/* Mobile pequeño (≤ 480px) */
@media(max-width: 480px){

 .brand-header {
    font-size: 1.8rem;
  }
 
  main h2 {
    font-size: 1.2rem;
  }
 
  .gallery li {
    padding: 5px;
  }
  
   
  .gallery li .box h3 {
    font-size: 0.9rem;
    letter-spacing: 1px;
  }
  
  .gallery li .box p {
    font-size: 1.2rem;
  }
  
 .gallery li .box .button {
    font-size: 0.9rem;
    padding: 8px;
  }
  
  .footer-nav ul li a {
    font-size: 0.85rem;
  }
 
  .footer-copyright {
    font-size: 0.75rem;
