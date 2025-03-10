Tracking System by Samarth Singh Chouhan
Track-Pharma
![214290533-35e7965e-1e43-4a18-8f7e-b2119b43266e](https://github.com/user-attachments/assets/84991e94-fce8-4869-a537-d7d1d11dfd12)

Description
A supply chain management solution for pharmaceutical products by TEAM201
Track-Pharma runs online at https://track-pharma.vercel.app/
Track-Pharma is a blockchain project by a collaborative effort of members of Team201. It is a decentralized application with which all parties involved in the pharmaceutical supply chain can easily create, store and retrieve certificates of each product history. This is provides an easy way to verify authenticity of pharmaceutical supplies and ensure compliance with standards.
![213938545-e689bbc6-6573-4a2c-aab9-79a8ec7fc92e](https://github.com/user-attachments/assets/3a356d54-bcad-4491-bf2f-25592371f196)
![214293128-93b15f3c-1d51-4886-8adf-20c4f0774e70](https://github.com/user-attachments/assets/b95a7fae-1e35-463b-909b-be2e66358f59)

The Problem
Pharmaceutical products’ monitoring authorities encounter difficulties in identifying unauthorized importers and manufacturers of substandard pharmaceutical products. Some of the existing means of keeping track of, and verifying the authenticity of pharmaceutical products, especially in developing countries are limited by the fact that methods of records management can be compromised. More so, with the possibility of regulatory officials being accomplices in the breach of regulatory measures, it has been a huge fight against drug abuse and counterfeiting in many countries.

Supply chains around the globe are confronted with significant interruption, and the lack of correspondence between key players in the supply chain can adversely affect production and distribution of vital pharmaceutical supplies. Among the effects of these problems have been drug resistance tendencies among the citizenry, caused by abuse of antibiotics and similar medications which do not meet the recommended standards.

The Solution
With more effective and trustless management of the supply chain of these products, pharmaceutical products manufacturers, distributors and retailers can eliminate the dark spots, while delivering trust-worthy products more timely and honorably. Though there have been existing technology-based systems by which the pharmaceutical industry has attempted to manage its products’ supply chain over the years, there have been limitations of inadequate transparency especially for large supply chains which often involve complex transactions.

Track-Pharma uses an user-friendly interface in its implementation as a supply-chain management system for pharmaceutical products

Track-Pharma_user_interface

Track-Pharma runs online at https://track-pharma.vercel.app/
The following Solidity functions are implemented in achieving developing the smart contract underlying Track-Pharma
image

The following are its spacifications:
Various user-roles i.e., the Manufacturers, Distributors, and Retailers of pharmaceutical products. The rules and protocols that make the Track-Pharma smart contract as developed using Hardhat
A blockchain network – Polygon Mumbai, for the Contract deployment. Particularly, Polygon Mumbai test network is used for this contract. A web-based user interface, using Next.js, Tailwind CSS, where users can access information. This is done with a number of assumptions as follows:

Items can only be listed into the database by a manufacturer who deploys the contract.
A distributor can be added to the database by the manufacturer from whom they buy products.
A distributor can in turn add retailers to the database and sell them products.
Retailers can add customers to the database and sell them products.
Every account handling various role except the end users (customers) must do this with an associated Metamask address.
All accounts have access to details of an item’s history along the supply chain as this is publicly accessible.
The following diagram gives a snapshot of user interaction and product path on Track-Pharma decentralized application.
Track-Pharma flow diagram

Track-Pharma is especially relevant in developing nations where importers of pharmaceutical supplies frequently circumvent national standards-setting laws. This solution will ensure that the manufacturer and location of production of certain pharmaceutical products can be clearly traced, and linked to the quality of each supply. Improved public access to high-quality pharmaceuticals and related products, which will result in a more effective healthcare system, will be one effect of this solution.

The increased transparency it fosters will deter and perhaps even terminate the illicit production, importation, and distribution of pharmaceutical goods in under-developed, as well as developing countries.

Getting Started
Installing

Executing program
Open the frontend folder in yoour choice IDE e.g. VSCode
Create a new file in the root folder and name it '.env'
Open the file 'env.example' and copy its content into the newly created '.env' file, this time, replacing the placeholder values with the respective values that apply.
In your terminal, navigate (cd) into the frontend folder and run one of the following commands according to your preference, to install dependences.
npm install
yarn install
Then run one of the following commands in the same terminal to start your local server for the frontend application and your interaction via a browser
npm run dev
yarn start
When the server is started, browse http://localhost:3000/ in your choice browser to see the app launched
Follow the guides and prompts available in the rendered frontend app to carry out transactions as you may desire for your testing
License
This project is licensed under the GNU License - see the LICENSE.md file for details
