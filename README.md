# Photography Site Showcase

The Photography Site is a complex web application project that I worked on in 2023. 

The main stack used in this project includes:
- ASP.NET 7.0, utilizing "Blazor Server" technology for creating pages and functionality, with C# as the main language.
- Entity Framework, used in conjunction with MySQL to provide databases.
- Google Calendar API for event synchronization.
- MudBlazor library for creating visual elements.
- ImageSharp library for resizing photos and creating watermarked versions.
- Deployment on Ubuntu with NGINX serving as a reverse proxy server.
- Utilization of Git version control technology for code management.

### I personally handled every aspect of the project, including prototyping, designing, programming, deployment, testing, and maintenance.

It's a comprehensive web application for order tracking, planning, and monitoring.

The website serves as an automated alternative to Bitrix24 or BaseCamp, integrating photography and album-making features. The app introduces work stages and time limits for each order, simplifying the order processing to a "conveyor belt". It allows all workers to perform their tasks independently, without requiring manual micro-management from the business owner and managers. It provides a single, well-organized platform that reduces the potential for mistakes caused by human factors. This application promotes work dedication, assists with employee management, and significantly enhances the client's capacity to handle a larger number of orders simultaneously, without needing to increase staff or time commitments. Moreover, it allows my customer to scale up their operations extensively because the app is designed to handle and support any volume of orders and workforce if necessary.

In the app, each order has a list of customers, each of whom has the right to make individual choices of photos they like. Each customer can only choose a pre-defined number of photos they have paid for. The photos they have chosen are then synchronized with the database table and can be viewed by the managers and all the workers connected to this order: photographers, designers, and sorters.

Each type of employee has their own obligations, where:
- Photographers register the participation of customers in a photosession, upload the original photos, and later edit all the photos that customers have chosen in the right way.
- Sorters check all the choices of customers and select photos for the customers who haven't picked them themselves.
- Designers use edited photos to create album models that will later be printed by a manager and provided to the clients.
- Managers track the stages of orders, reach out to customers who didn't participate in a photosession, schedule new photosessions, place orders for album printing, and track the delivery of albums to the customers.
- The owner of the business controls finances and payments.

The main page of the site from the Managers view looks like this (dark mode is ON):
![site](https://github.com/J3ster1337/PhotographySiteShowcase/assets/130294475/8d0778b3-cb5b-4427-a6e4-a6a4cc619f7f)
1. The navigation menu has links to all pages for all types of workers, in case the manager needs to interact with their part of the work.
2. A list of clients who have never participated in any photoshoot and need to be contacted.
3. An editable list of albums that can be selected by clients. Each album has its own characteristics and price.
4. A page where all site users accounts can be viewed and edited.
5. A page where all income and expenses can be seen. (Only visible to the owner and admin).

The order page looks like this (dark mode is OFF):
![site2](https://github.com/J3ster1337/PhotographySiteShowcase/assets/130294475/e828c36b-906b-4b11-96f9-8678b8539584)
1. A column with links and information connected to the portraits part of the work.
2. A column with links and information connected to the reportages part of the work.
3. The current stage of the type of work and a timer associated with it.
4. A button that opens an external link to the contract file. The link can be edited.
5. Copy-buttons with links that will later be sent to clients so they can download their files.
6. A section of the site that allows the manager to schedule new photosessions. Each photosession is later synchronized with the Google Calendar of the chosen photographer.
7. Information about the previously completed photosession.

The list of the clients inside the order looks like this:
![site3](https://github.com/J3ster1337/PhotographySiteShowcase/assets/130294475/1af1ce2e-929c-4a19-98fa-86d903739cae)

# And much more, including:
- Automatic creation of compressed and watermarked versions of photos for when clients choose the photos for the album.
- Client-side page for picking photos that allows for photo buy-out and ordering of "additional pages" for the album.
- Runtime creation of downloadable archives with files, both for workers and clients.
- Automatic replacement of photos with their edited versions during the upload by the photographer.
- Synchronization between the database part of the photo and its file (both compressed and uncompressed).
- Various pages for all types of workers that meet their specific needs.
- Different customizable types of access to orders for all roles of workers.
- Complex stages system for orders.
- Clean architectural structure that allows for fast implementation of new features.
- Extremely low usage of computing power due to efficient programming, resulting in reduced server cost expenses. Additionally, despite the low utilization of computing resources, the app's performance remains exceptional, delivering a seamless user experience.
