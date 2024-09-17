# Html-css-work-1
THis is My first Projrct in Html css 
![Screenshot 2024-09-17 195749](https://github.com/user-attachments/assets/d66df655-bccf-423f-a2c2-7d010a3ecda4)
This is the output of the code which is down 





  [Uploading index.h<!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Recipes</title>
      <link rel="stylesheet" href="/style.css" />
    </head>
    <body>
      <!-- nav  -->
      <nav class="navbar">
        <div class="nav-center">
          <div class="nav-header">
            <a href="index.html" class="nav-logo">
              <img src="./assets/logo.svg" alt="simply recipes" />
            </a>
            <button class="nav-btn btn">
              <i class="fas fa-align-justify"></i>
            </button>
          </div>
          <div class="nav-links">
            <a href="index.html" class="nav-link"> home </a>
            <a href="about.html" class="nav-link"> about </a>
            <a href="tags.html" class="nav-link"> tags </a>
            <a href="recipes.html" class="nav-link"> recipes </a>
            <a href="404.html" class="nav-link"> 404 </a>
  
            <div class="nav-link contact-link">
              <a href="contact.html" class="btn"> contact </a>
            </div>
          </div>
        </div>
      </nav>
      <!----main------->
      <main class="page">
          <header class="hero">
              <div class="hero-container">
                  <div class="hero-text">
                      <h1>Simply Recipes</h1>
                      <h4>No fluff, Just recipes</h4>
                  </div>
              </div>
          </header>
          <section class="recipes-container">
              <div class="tags-container">
                  <h4>recipes</h4>
                  <div class="tags-list">
                      <a href="tag-template.html">Beef (1)</a>
                      <a href="tag-template.html">Breakfast (2)</a>
                      <a href="tag-template.html">arrot (3)</a>
                      <a href="tag-template.html">Food (4)</a>
                  </div>
              </div>
              <div class="recipes-list">
                  <a href="single-recipe.html" class="recipe">
                      <img src="./assets/recipes/recipe-1.jpeg" alt="Food" class="img recipe-img">
                      <h5>carne asada</h5>
                      <p> prep : 15min | Cook : 5min</p>
                  </a>
                  <a href="single-recipe.html" class="recipe">
                      <img src="./assets/recipes/recipe-2.jpeg" alt="Food" class="img recipe-img">
                      <h5>Greek ribs</h5>
                      <p> prep : 15min | Cook : 5min</p>
                  </a>
                  <a href="single-recipe.html" class="recipe">
                      <img src="./assets/recipes/recipe-3.jpeg" alt="Food" class="img recipe-img">
                      <h5>vegetable soap</h5>
                      <p> prep : 15min | Cook : 5min</p>
                  </a>
                  <a href="single-recipe.html" class="recipe">
                      <img src="./assets/recipes/recipe-4.jpeg" alt="Food" class="img recipe-img">
                      <h5>Banana pancakes</h5>
                      <p> prep : 15min | Cook : 5min</p>
                  </a>
              </div>
          </section>
      </main>
  
  
      <!---Page-footer-->
      <footer class="page-footer">
          <p>
              &copy;<span id="date">2023</span>
              <span class="footer-logo">SimplyRecipes</span>
              Built BY <a href="#">SamiKhan </a>
          </p>
      </footer>
      <script src="/app.js"></script>
  </body>
  </html>    tml.html…]()


     \.btn{
    background-color: blue;
    color: white;
    border-radius: 6px;
}
.navbar {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .nav-center {
    width: 90vw;
    max-width: var(--max-width);
  }
  .nav-header {
    height: 6rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .nav-header img {
    width: 200px;
  }
  .nav-logo {
    display: flex;
    align-items: flex-end;
  }
  
  .nav-btn {
    padding: 0.15rem 0.75rem;
  }
  .nav-btn i {
    font-size: 1.25rem;
  }
  .nav-links {
    height: 0;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    transition: var(--transition);
  }
  .show-links {
    height: 23.9375rem;
  }
  
  .nav-link {
    display: block;
    text-align: center;
    font-size: 1.25rem;
    text-transform: capitalize;
    color: var(--grey-900);
    letter-spacing: var(--letterSpacing);
    padding: 1rem 0;
    border-top: 1px solid var(--grey-500);
    transition: var(--transition);
  }
  .nav-link:hover {
    color: var(--primary-500);
  }
  
  .contact-link a {
    padding: 0.15rem 1rem;
  }
  
  @media screen and (min-width: 992px) {
    .navbar {
      height: 6rem;
    }
    .nav-center {
      display: flex;
      align-items: center;
    }
    .nav-header {
      padding: 0;
      margin-right: 2rem;
      height: auto;
    }
  
    .nav-btn {
      display: none;
    }
    .nav-links {
      height: auto !important;
      flex-direction: row;
      align-items: center;
      width: 100%;
    }
    .nav-link {
      padding: 0;
      border-top: none;
      margin-right: 1rem;
      font-size: 1rem;
    }
    .contact-link {
      margin-right: 0;
      margin-left: auto;
    }
    }
    .page{
        width: 90vw;
        max-width: var(--max-width);
        margin: 0 auto;
        padding-top: 2rem;
        min-height: calc(100vh - (6rem + 4rem));
    }
    /* main */

    .hero {
        height: 40vh;
        position: relative;
        margin-bottom: 2rem;
        background: url('../assets/main.jpeg') center/cover no-repeat;
        border-radius: var(--borderRadius);
      }
      .hero-container {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
        background: rgba(0, 0, 0, 0.4);
        border-radius: var(--borderRadius);
      }
      .hero-text {
        color: var(--white);
        text-align: center;
      }
      
      @media only screen and (min-width: 768px) {
        .hero-text h1 {
          font-size: 4rem;
          margin-bottom: 0;
        }
      }
      
      /*-----Recipes----*/
      
      .recipes-container {
        display: grid;
        gap: 2rem 1rem;
      }
      
      .recipes-list {
        display: grid;
        gap: 2rem 1rem;
        padding-bottom: 3rem;
      }
      .tags-container {
        order: 1;
        display: flex;
        flex-direction: column;
        padding-bottom: 3rem;
       
      }
      .tags-container h4 {
        margin-bottom: 0.5rem;
        font-weight: 500;
      }
      .tags-list {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
      }
      .tags-list a {
        text-transform: capitalize;
        display: block;
        color: var(--grey-500);
        transition: var(--transition);
      }
      .tags-list a:hover {
        color: var(--primary-500);
      }
      .recipe {
        display: block;
      }
      .recipe-img {
        height: 15rem;
        border-radius: var(--borderRadius);
        margin-bottom: 1rem;
      }
      .recipe h5 {
        margin-bottom: 0;
        margin-top: 0.25rem;
        line-height: 1;
        color: var(--grey-700);
      }
      .recipe p {
        margin-bottom: 0;
        line-height: 1;
        color: var(--grey-500);
        margin-top: 0.5rem;
        letter-spacing: var(--letterSpacing);
      }
      @media screen and (min-width: 576px) {
        .recipes-list {
          grid-template-columns: 1fr 1fr;
        }
        .recipe-img {
          height: 10rem;
        }
      }
      
      @media screen and (min-width: 992px) {
        .recipes-container {
          grid-template-columns: 200px 1fr;
          gap: 1rem;
        }
        .recipes-list {
          grid-template-columns: 1fr 1fr;
        }
      
        .recipe p {
          font-size: 0.85rem;
        }
        .tags-container {
          order: 0;
          
        }
        .tags-list {
          display: grid;
          grid-template-columns: 1fr;
        }
      }
      
      @media screen and (min-width: 1200px) {
        .recipe h5 {
          font-size: 1.15rem;
        }
        .recipes-list {
          grid-template-columns: 1fr 1fr 1fr;
        }
      }









   .page-footer{
    height: 4rem;
    display: flex;
    align-items: center;
    justify-content: center;
    background: black;
    color: white;
}
.page-footer p{
    margin-bottom: 0;

}
.footer-logo ,.page-footer a{
    color: var(--primary-500);
}

/*----Error-page-----*/
.error-page{
    text-align: center;
    padding-top: 5rem;
}
.error-page h1{
    font-size: 9rem;
}

/*------About-----*/


.about-page h2 {
    text-transform: none;
    font-weight: bold;
}
.about-page {
    display: grid;
    gap: 2rem 4rem;
    padding-bottom: 3rem;
}
.about-img {
    border-radius: var(--borderRadius);
    height: 300px;
}
@media screen and (min-width: 992px) {
    .about-page {
        grid-template-columns: 1fr 1fr;
        grid-template-rows: auto; /* Use auto for flexible height based on content */
        align-items: center;
    }

    .about-img {
       
        border-radius: var(--borderRadius);
        
    }
}

  
  .featured-title {
    text-align: center;
  }         
