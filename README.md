**# WikipediaClone**
![image](https://github.com/user-attachments/assets/85d0410f-5677-42d2-8e33-3cfc84fd1a25)

![image](https://github.com/user-attachments/assets/7be724b2-cad2-4782-ad6a-1eb2645cd969)






**Overview:**
This project is a simplified Wikipedia Clone built using HTML, CSS, and JavaScript, with integration of the Wikipedia API to fetch real-time articles and information. The clone aims to replicate the look and feel of Wikipedia’s basic structure and provide a similar user experience while offering search capabilities for Wikipedia articles.

**Features:**_
Search Functionality: Users can search for any topic or keyword to fetch relevant Wikipedia articles.
Responsive Design: The layout is fully responsive, providing a smooth user experience across different devices.
Real-time Data: Data is fetched in real-time from Wikipedia’s official API, ensuring the information is always up to date.
Minimalist UI: The interface mimics the simple, user-friendly design of Wikipedia, focusing on readability and usability.
Technologies Used
HTML5: For structuring the content and layout of the website.
CSS3: For styling the elements and making the design responsive and visually appealing.
JavaScript: For handling the dynamic functionalities like API requests and rendering data.
Wikipedia API: To retrieve article data from Wikipedia based on user searches.

**Project Structure:**

wikipedia-clone/
├── index.html        # Main HTML file
├── styles/
│   └── style.css     # Custom CSS styles
├── scripts/
│   └── app.js        # Main JavaScript file handling API calls and UI updates
└── README.md         # Project description and details


**How to Run the Project**

1. Clone this repository:
git clone https://github.com/your-username/wikipedia-clone.git

2. Open the project directory:
cd wikipedia-clone

3. Open index.html in your browser to view the Wikipedia Clone.

**API Integration**
This project uses the Wikipedia API to fetch data. To perform a search, a GET request is made to the API with the search query entered by the user. The relevant articles are then displayed on the page in real time.

**Example API request:**
fetch(`https://en.wikipedia.org/w/api.php?action=query&list=search&format=json&origin=*&srsearch=${query}`)
  .then(response => response.json())
  .then(data => {
    // Handle data
  })
  .catch(error => {
    console.error('Error fetching data:', error);
  });


Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.

1.Fork the repository.
2.Create a new branch: git checkout -b feature-branch.
3.Make your changes and commit them: git commit -m 'Add new feature'.
4.Push to the branch: git push origin feature-branch.
5.Submit a pull request.


**Acknowledgements**
=>Wikipedia API Documentation
=>MDN Web Docs
















