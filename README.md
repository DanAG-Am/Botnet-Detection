# Botnet-Detection
This project leverages advanced data structures, specifically **Linked Lists** and **Binary Search Trees (BST)**, to help detect potential **botnet** activities within a network. A **botnet** is a network of compromised devices controlled remotely by a malicious actor, often used for launching large-scale attacks like DDoS or spamming.

**Linked Lists**: Used for storing and managing network log data, where each entry represents a unique network request or device interaction. Linked lists are ideal for dynamic data where the size can vary over time.
- **Binary Search Trees (BST)**: Used for efficient searching and organization of device IPs and other critical data attributes. BSTs allow us to quickly check if an IP address or device has been involved in malicious behavior by keeping the data sorted and allowing for logarithmic search times.

### Linked List:
Linked lists are used to store network logs or activity entries, where each node contains details such as the device IP, timestamp of the request, and the action performed. They allow us to efficiently handle dynamic data that continuously grows as new logs come in.

### Binary Search Tree (BST):
A Binary Search Tree is utilized to store device IP addresses, tracking their activity over time. The tree helps efficiently search for existing entries to see if an IP has been flagged for suspicious activity. BSTs ensure that the system can scale by offering logarithmic time complexity for search, insert, and delete operations.
