# How To Add New Products in WooCommerce?
Adding new products in WooCommerce is fairly easy, for as long as you have the needed details regarding the products to be added.

As a prerequisite, you must be logged in to WordPress admin backend, and have WooCommerce already installed.

### 1. On the left side tab, look for the WooCommerce section.
You should be able to see this once WooCommerce is installed and set up.
### 2. Hover over the Products button.
While hovering, a submenu will show. Click on `Add new product` button.
### 3. Put all of the needed product details once on the page.
Here's the following vital fields you will need to fill up:
- `Product Name`: This is where the product name goes. Try to make an engaging product title for your specific product.
- `Product Description`: This is where the product description goes. Try to be detailed as possible with the product specs, while creating an engaging general product description.
- `Publish`: This is where you see the publishing status of the product. By default, the product gets autosaved as a draft before being live on the site. Here, you can also edit the product visibility on the frontend.
- `Product Image`: This is where the hero image goes, which also appears on menus of the site frontend. Do upload a nice product shot for the listing, as it would help with customer engagement.
- `Product Gallery`: If you have two or more images other than the hero image, this is where you'll be putting the other images that would be seen on the product page.
- `Product Categories`: This is used to categorize the listing into separate collections. You can either select one of the available categories, or you can create a new one if it doesn't fall into any of the existing categories.
- `Product Tags`: This is also another way to categorize products, especially if you want to categorize the product into something more specific.
- `Brands`: If you have a branded product in your site, this is mainly used to create brand-specific categories.
- `Meta Description`: This is the description that you will see on search engine results. Feel free to edit this to optimize SEO rankings.
- `Product Short Description`: This is the description that would appear right below the product title on the frontend product page. If this is left blank, the main product description will appear in its place on the frontend. For better SEO hygiene, try to make a different, shorter description than the main description, since the main product description will also hold the product specs, if ever.

Once these are all filled up, we are ready for the next step.
### 4. Publish the Product
Using the third bullet point from the previous step, just click on the`Publish` button.

# How To Create A New Category Page
In WP/WooCommerce, product collections are divided into product categories. This is very important since this is where you can actually partition the products into their proper categories, for easier access for customers. 
### 1. On the dashboard, hover over the Products button.
While hovering, choose the `Categories` button to go to the page. 
### 2. On the Categories page, go to the `Add new category` section.
From there, you can input the needed vital details for the category to be created.
- `1) Name`: here, you can name the category collection. Choose the appropriate collection name for a specific category, which in the site's case, an example is the `Peripherals` category.
- `2) Slug`: this is how the URL will look like on a live site. Taking the example above, the slug is `peripherals`, which in the frontend will look like `https://cpostechnologies.com/product-category/peripherals/`.
- `3) Description`: this is where the description of the category goes. Try putting an engaging, SEO-friendly description in relation to the category contents. For now, we can leave `Parent category` and `Display type` fields for now, for tutorial purposes. Next up once we've created our new product category, we can now put the category on the Header Navi. 

# How To Add The New Product Category In The Header Navi
This process might be confusing at first, but as long as we know where to go, it's actually pretty simple. 

### 1. On the dashboard, hover over the Appearance button.
While hovering, choose the `Editor` button to go to the page. 
### 2. Once on the Site Editor page, click on the Header Navi.
From there, you'll need to access the settings bar on the right side. 
### 3. On the Settings bar, add the submenu entry for the desired category page.
- You should be on the Navigation settings by now. Click on the meatball button beside the `Products` entry.
- On the dropdown menu after clicking, click on the Add Submenu Link button to add a new entry.
- Edit the new entry by clicking the new entry, named Custom Link by default. - Edit the `Text` and `Link` button to reflect the new category. The URL to be used for the Link should be `cpostechnologies.com/product-category/[URL Slug]/`, with the URL slug taken from the Slug field of the created category.
