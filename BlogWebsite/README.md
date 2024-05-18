# Dependencies used
- @reduxjs/toolkit
- react-redux 
- react-router-dom
- appwrite
- @tinymce/tinymce-react
- html-react-parser
- react-hook-form

# Environmental Variable 
1. Rules for access were different for React, backend, vite, etc
2. Must not be shared. So, added in .gitignore
3. IN React app : we have to name environmental varible with REACT_APP_VARIABLE_NAME
4. And to Excess them : process.env.REACT_APP_VARIABLE_NAME
5. In VITE app : We have to name environmental varible with VITE_VARIABLE_NAME
6. And to access them : import.meta.env.VITE_VARIABLE_NAME

# Appwrite IDs
- Take all the id that we rerquired from appwrite that we use as a backend service in this project
- Simply create a new Projects -> setup database -> setup storage and get there ids
