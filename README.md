# Microservices Test Deployment on IBM Cloud Engine

This project involves the deployment of multiple microservices for a dealership of a product comparison platform. The system is composed of three key microservices:

1. **Product Details Microservice (Python)**: Provides information about products available for comparison.
2. **Dealer Pricing Microservice (Node.js)**: Supplies pricing from various dealers for the listed products.
3. **Dealer Evaluation Frontend Microservice**: Serves as the user-facing interface, allowing customers to search for products, view dealer information, and compare prices based on the backend microservices' data.

Each microservice has been deployed using IBM Code Engine, a serverless platform that ensures scalable, efficient, and cost-effective cloud-native deployments. The front-end microservice is integrated with the backend to showcase seamless communication between the microservices. Users can select products from a dropdown list, view available dealers, and compare pricing across multiple dealers.

### Technologies Used:
- Python (for Product Details microservice)
- Node.js (for Dealer Pricing microservice)
- HTML, CSS, and JavaScript (for the Frontend)
- IBM Code Engine for serverless deployment

### How to deploy
After deploying the two backend apps - product and dealer, replace the product and dealer apps' URL in the index.html file of the frontend application 

This project highlights the ability to deploy and integrate microservices efficiently in a cloud-native environment, providing real-time product and pricing comparisons.

### Courtesy
IBM Skills Network & Lavanya (Author)
