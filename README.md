
# ecommerce site
I wanted to try and make a more commercial site using next.js. I used a great service called Sanity to manage the content of the app which then acted as the backend.

[Live Site](https://ecommerce-ek.vercel.app/)

## Features
- Editable hero and footer banners that can be easily updated using Sanity.
- Cards for each product.
- Further details page for each product.
- Add to cart or buy now buttons.
- Scrolling banner of products you may also like.
- Cart / Basket where you can increase or decrease the number of products as well as remove an item entirely.
- Full intergration with Stripe to process payments.
- Congratulation on purchase page as well as an email notifying you of your purchase.

## Installation
```bash
git clone https://github.com/Elkennard/weather-app-react.git
cd ecommerce
npm i
```

## Running Application
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You will aso need to setup free accounts with Sanity and Stripe as well as an .env file in the route folder with the following credentials...
```bash
NEXT_PUBLIC_SANITY_TOKEN = 
NEXT_PUBLIC_STRIPE_PUBLISHBLE_KEY =
NEXT_PUBLIC_STRIPE_SECRET_KEY =
```
## Tech Stack
<div align="left">
<a href="https://beta.reactjs.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="50" /></a>
<a href="https://nextjs.org/" target="_blank"><img style="margin: 10px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Nextjs-logo.svg/800px-Nextjs-logo.svg.png" alt="Next.js" height="50"/></a>
<a href="https://www.sanity.io/" target="_blank"><img style="margin: 10px" src="https://cdn.worldvectorlogo.com/logos/sanity.svg" alt="Sanity" height="50"/></a>
<a href="https://stripe.com/gb" target="_blank"><img style="margin: 10px" src="https://media.designrush.com/inspiration_images/135143/conversions/_1510164528_150_social-mobile.jpg" alt="Stripe" height="50"/></a>
<a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="50" /></a>
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" /></a>
<a href="https://github.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" /></a>
<a href="https://babeljs.io/" target="_blank"><img style="margin: 10px" src="https://d33wubrfki0l68.cloudfront.net/7a197cfe44548cc1a3f581152af70a3051e11671/78df8/img/babel.svg" alt="Babel" height="50"/></a>
<a href="https://vercel.com/" target="_blank"><img style="margin: 10px" src="https://logovtor.com/wp-content/uploads/2020/10/vercel-inc-logo-vector.png" alt="Vercel" height="50"/></a>
</div>

## Acknowledgements
Created using the following tutorial on [YouTube](https://www.youtube.com/watch?v=4mOkFXyxfsU)