Documentation
=======================
#### OpenPhoto, a photo service for the masses

----------------------------------------

### What's a User object for?

The User object stores information for a given user.
This includes the last uploaded [Photo][Photo]  and [Action][Action] id.

----------------------------------------

### Schema for a User object

    {
      id: (string),
      lastPhotoId: (string),
      lastActionId: (string)
    }

----------------------------------------

### Schema description

  * id, the user id
  * lastPhotoId, most recent photo id
  * lastActionId, most recent action id

[User]: User.markdown
[Photo]: Photo.markdown
[Action]: Action.markdown
