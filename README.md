

# Flash-Chat

One of the most fundamental component of modern iOS apps is the Table View. Table Views are used everywhere from the Mail app to the Messages app. It’s a crucial part of every iOS developer’s tool belt. In this tutorial we’ll be getting to grips with Table Views, creating custom cells, and making our own cloud-based backend database. It’s going to be epic, so buckle up.


# Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

```
![End Banner](Documentation/readme-end-banner.png)
