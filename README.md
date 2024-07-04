# Daily_Blogs_Backend

## Overview

Daily_Blogs_Backend is a **FastAPI-based** backend service for managing daily blog entries. It includes functionality for creating, reading, updating, and deleting blog posts stored in a SQLite database.

## Features

- **Create Blog Posts**: Add new blog entries.
- **Read Blog Posts**: Retrieve and display existing blog entries.
- **Update Blog Posts**: Modify existing blog entries.
- **Delete Blog Posts**: Remove blog entries.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/N16H7H4WK-3R/Daily_Blogs_Backend.git
   ```

2. Navigate to the project directory:
    ```bash
    cd Daily_Blogs_Backend
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```


## Usage

1. Run the main application:

```bash
    uvicorn main:app --reload
```

2. The backend service will start, and you can interact with it using your preferred method (e.g., FastAPI interactive docs, cURL, Postman).


## Project Structure

- **main.py :** Entry point for the application.
- **blog/ :** Contains modules and packages for handling blog functionalities.
- **blog.db :** SQLite database file.
- **requirements.txt :** List of dependencies required for the project.
- **.gitignore :** Specifies files and directories to be ignored by git.

## Technologies Used

- **Python :** Main programming language.
- **FastAPI :** Web framework for building the backend service.
- **SQLite :** Database for storing blog entries.


## License

This project is licensed under the MIT License. See the **LICENSE** file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.

## Contact

- **For any questions or feedback, please open an issue in the repository.**

- **Feel free to modify the content as per your specific requirements.**
