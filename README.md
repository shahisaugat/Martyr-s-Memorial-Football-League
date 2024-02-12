# Martyr's Memorial Football League
Martyr's Memorial Football League is a application 
that gives you personalized information about the local and national football 
tournaments and detailed information about the history and foundation of a club as well.

![Application Logo Theme](Images/logonp1.png)

## Features
- Data Integrity and Security
- Personalized Profile
- Club and Player's Information
- Search Functionality
- Match Statistics
- Live Streaming

## Installation
- You need to have Python and an IDE.
- MongoDB needs to be installed.
- Setup MongoDB and set the connection port.

```Python
try:
    # Creating MongoClient, connecting to database and collection
    football_client = MongoClient('mongodb://localhost:27017/')
    football_database = football_client['football_database']
    football_collection = football_database['users']
except:
    messagebox.showerror('Error','Database Connection Error')
```


| Example Account | Example Password |
|-----------------|------------------|
| 123456789       | Admin@123        |


## GitHub Repository
[GitHub Main](https://github.com/saugatshahi)
