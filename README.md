# Python-social-media
twitter tutorial
# Creation of the actual interface, using authentication
api = tweepy.API(auth)
 
# Sample method, used to update a status
# api.update_status('Hello I am creating a python youtube tutorial!')

# Creates the user object. The me() method returns the user whose authentication keys were used.
user = api.me()
