# e-commerce
A sustainable e-commerce application. It features a carbon footprint rating system, circular economy donations to environmental organizations, and a product recycling and disposal program. 
# Sustainable E-Commerce Application

This is the README file for the Sustainable E-Commerce Application developed using Django and RESTful API.

## Description

The Sustainable E-Commerce Application is an online platform that promotes sustainability and eco-conscious shopping. It provides various features to help customers make environmentally friendly choices and contribute to a sustainable economy.

### Features

- Carbon Footprint: Each product is rated based on its carbon footprint, which is extracted from the supplier's data. The carbon footprint rating helps customers make environmentally conscious choices.
- Circular Economy: Customers can choose to donate a portion of their purchase to environmental organizations, supporting initiatives for a sustainable economy.
- Recycling and Disposal: The application allows customers to return products at the end of their life cycle for recycling or proper disposal, reducing waste and promoting sustainable practices.

## Project Progress

Please note that this project is currently under development. The following sections highlight the completed parts and the parts that are still in progress.

### Completed Features

- Django and RESTful API setup
- Customization of the User model with email field
- Product model with carbon footprint rating
- Collection model for organizing products
- Customer model for user information
- Cart and CartItem models for shopping functionality
- Review model for customer feedback
- Custom admin configurations
- URL patterns for products, collections, and carts

### Work in Progress

The following features are currently being developed:


- Circular Economy donation feature
- Recycling and disposal feature
- Sending Emails
- Uploading Files
- Caching

## Installation

To run the Sustainable E-Commerce Application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/shirinrahmani90/Sustainable-E-commerce`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Set up the database by running migrations: `python manage.py migrate`
4. Start the development server: `python manage.py runserver`

## Usage

1. Access the application by navigating to `http://localhost:8000` in your web browser.
2. Explore the available products and collections.
3. Add products to your cart and proceed to checkout.
4. Provide the required information and complete the purchase. (Under Development)
5. Consider donating a portion of your purchase to support environmental organizations. (Under Development)
6. At the end of a product's life cycle, utilize the recycling and disposal feature for responsible waste management.(Under Development)

## Contributing

If you would like to contribute to the Sustainable E-Commerce Application, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b my-new-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

## License

[MIT License](LICENSE)
