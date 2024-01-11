# SQL-Project---Real-Estate-Management-System

This SQL project is a Real Estate Management System that facilitates the tracking and management of various properties, including houses and business properties. The system also manages information about agents, firms, and buyers. Below is an overview of the entities involved in the project:

## Entities:

### Property
- **Attributes:**
  - Address
  - Owner’s name
  - Price

### House
- **Additional Attributes:**
  - Number of bedrooms
  - Number of bathrooms
  - Size in square feet

### Business Property
- **Additional Attributes:**
  - Type of business (e.g., gas station, store front, office space)
  - Size in square feet

### Agent
- **Attributes:**
  - ID
  - Name
  - Phone number
- **Employment Record:**
  - Start date of employment

### Firm
- **Attributes:**
  - ID
  - Name
  - Address

### Buyer
- **Attributes:**
  - ID
  - Name
  - Phone number
  - Preferences:
    - Type of property (house or business property)
    - Desired attributes (if a house is preferred)

## Project Structure:

The SQL project consists of tables for each entity, capturing their respective attributes and relationships. Relationships among entities are established through foreign keys and associations.

## Queries:

A set of SQL queries has been designed to perform various operations, including property listings, agent details, buyer preferences matching, and more. Refer to the queries section for specific use cases.

## Queries:

1. **[1st Query](#1st-query):** Retrieve the addresses of listings associated with houses.
2. **[2nd Query](#2nd-query):** Retrieve the addresses and MLS numbers of listings associated with houses.
3. **[3rd Query](#3rd-query):** Find the addresses of listings associated with houses having 3 bedrooms and 2 bathrooms.
4. **[4th Query](#4th-query):** Retrieve addresses and prices of houses with 3 bedrooms, 2 bathrooms, a price between $100,000 and $250,000, and order the results by price in descending order.
5. **[5th Query](#5th-query):** Retrieve addresses and prices of business properties of type 'office space'. Order the results by price in descending order.
6. **[6th Query](#6th-query):** List the agent ID, name, phone number, firm name, and start date for all agents along with their respective firms.
7. **[7th Query](#7th-query):** Retrieve all details of properties listed by an agent with the ID 201. Include information about the properties associated with this agent.
8. **[8th Query](#8th-query):** Provide a list of agent names and corresponding buyer names who have worked together.
9. **[9th Query](#9th-query):** Retrieve details of houses matching the preferences of a buyer with ID 799.
