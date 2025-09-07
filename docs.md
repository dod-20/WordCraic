# Adding a New Lesson

To add a new lesson to the app, follow these steps:

## 1. Create the lesson JSON
- Go to the correct tense folder
- Add a new JSON file for your lesson

## 2. Register the lesson in course metadata
- Open the metadata file for that tense:
- Add an entry for your new lesson, so the app knows it exists.

## 3. Update the database
Currently, there are two options here (depending on how you handle updates):
- **Rebuild the database** (clear and reinitialize) to load the new lesson.  
- Or **add the new lesson into the existing database** manually, if update logic is implemented. 
