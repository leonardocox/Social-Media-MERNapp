# Post

|     Object      |      Relation      |
| :-------------: | :----------------: |
|      \_id       |       String       |
|     userId      |     String Ref     |
|    firstName    |       String       |
|    lastName     |       String       |
|    location     |       String       |
|   description   |       String       |
| userPicturePath |     String Ref     |
|   picturePath   |     String Ref     |
|      likes      | Object<String Ref> |
|    comments     |   Array<String>    |

# User

|    Object     |   Relation    |
| :-----------: | :-----------: |
|     \_id      |    String     |
|   firstName   |    String     |
|   lastName    |    String     |
|    friends    | Array<Object> |
|     email     |    String     |
|   password    |    String     |
|  picturePath  |  String Ref   |
|   location    |    String     |
|  occupation   |    String     |
| viewedProfile |    Number     |
|  impressions  |    Number     |
