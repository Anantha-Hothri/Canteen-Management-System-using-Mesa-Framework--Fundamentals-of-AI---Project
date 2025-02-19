AI-Agent Module for Canteen Management System
This module leverages intelligent agents built using the Mesa framework to automate and enhance the canteen management process. It includes server-client communication scripts, dynamic menu generation, and comprehensive documentation.

Files in this Folder : 
----------------------
1. AI_Server.py
Description:
This script acts as the central server for the system, handling requests and managing order processing.

Key Features:
Processes user orders sent by the client.
Generates a unique token for each order.
Ensures secure and efficient server-side operations.

Purpose:
Facilitates seamless communication between the user (client) and the server.

=========================================================================================================================================
2. AI_Client.py
Description:
This script provides a user interface for the ordering process. It interacts with the server to send orders and retrieve tokens.

Key Features:
Displays dynamic menus generated by intelligent agents.
Allows users to place orders.
Receives and displays unique tokens from the server.

Purpose:
Simplifies the order placement process, ensuring a smooth user experience.

=========================================================================================================================================
3. DynamicMenuAgent.py
Description:
This script uses the Mesa framework to create and manage intelligent agents for dynamic menu updates.

Key Features:
Generates menus based on real-time data such as the time of day.
Automates menu management tasks.
Integrates with other system components for seamless operation.

Purpose:
Enhances user experience by providing real-time, context-aware menu options.