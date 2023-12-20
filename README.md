### Data changing via Charles web degubbing proxy

According to the task I tested [webshop cart](http://demowebshop.tricentis.com/cart) using Charles proxy.

Check out the following videos where I'm changing data using the proxy server for website on Google Chrome on my laptop: 

- [Changing the number of items in the cart](https://photos.app.goo.gl/SECtjB4ApFhN2ct19) Changing the number of items in the cart. </a>  The request sends 2 items and returns 500;
- [Changing the response status from 200 to 403.](https://photos.app.goo.gl/LsxKdJ25LxF8ttHd7) Changing the response status from 200 to 403. </a> using block list;
- [Redirecting the request](https://photos.app.goo.gl/vziBvbxWpve9jFSc7) from Prod environment "demowebshop.tricentis.com" to QA environment "demowebshop.tricentis.com/qa" using map remote. 

Also i had changed data using the proxy server for the same website on my Samsung Galaxu Tab connected to Android studio: 

- [All goods from shopping cart have been deleted](https://photos.app.goo.gl/bJWL2GPUcxEKwN9Y8) using breakpoint
- [Redirecting to random picture](https://photos.app.goo.gl/fGm3LuWAhjSJVLbv9) using map local