## Stack Overflow App
# Requirements :

# Actors:
    - Guest Users (people not logged in)
        Functionality : 
            - See posts
            - Search 
            - View questions
            - Can search topics or people who have written some content
    - Logged In Users 
        Functionality: 
            - Can rate questions
            - Can add questions
            - Can answer questions
            - Can add comments to a question
    - Moderator 
        Functionality: 
            - Close questions or open questions / threads
            - Can delete question
            - Can restore question 
            - Can delete answer 
    - System Admin 
        Functionality: 
            - Block users
    _______
    - Creating a question 
        - Filtering tags
# UseCases 
    - Guest can search or view a question 
    - Normal user can login , logout, reset password
    - Normal user can up vote, down vote, flag a question, answer a question
    - Moderator can open questions, restore questions, close questions
    - Admin can block users and unblock users
    - System can send notifications 
# Relationships
    - Moderator is an extension of a Normal user
    - Questions have a relationship between tags

# UseCase Diagram > Class Diagram > Sequence Diagram. 

# Searching : how can a guest search by tag, 
#Actions 