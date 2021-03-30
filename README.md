<!-- cmd shift v to preview -->

## Project Proposal

Mindful Everyday - M.E.

### Overview

ME is a daily journal application where users will be able to log in and create daily entries which include gratitude, activity, sleep (quality and quantity), meditation, a daily goal, water intake, top three emotions, and endless writing to reflect upon the day. Users will also be able to go back and look at past entries.

Intention:
To empower users to learn more about themselves. To tune into how their daily choices and activities affect their mood and energy.

Future goals:
Diagram statistics based on user input.

### Technologies required (besides typical Hackbright tech stack)

- Zen Quotes API - https://zenquotes.io/

### Data

- User

  - user_id (Integer, Primary key, auto increment)
  - fname (varchar/string(100))
  - lname (varchar/string(100))
  - email (varchar/string(100))
  - dob (date)

- Morning Entry

  - am_entry_numbe (Integer, primary key, auto increment)
    Or do I want this to be uniquely defined by the date?
  - hours_slee (Integer)
  - quality_slee (Want to have either drop down or scale from 1-10)
  - journal_entry (varchar/string(2000))
  - gratitude (Three entries for each day)
  - intention/goal for the day (varchar/string(300))

- Evening Entry
  - pm_entry_number (Integer, primary key, auto increment)
    - Or do I want this to be uniquely defined by the date?
  - Emotions (varchar/string(100))
  - List of three emotions
  - activity (Integer)
  - complete_intention/goal (boolean)
  - journal_entry (varchar/string(2000))
    - Want to have a minimum requirement of 1 word

### Roadmap

#### MVP

- Users can create a login
- Daily entries
- View all past entries

#### 2.0

- Overview chart of emotions
- UI styling
- Share with friends?
- Show local exercise classes to promote moving your body

#### 3.0

- Upload a photo for the day
- Integrate workout apps information
- Look for people in your area from the app who want to meet up for outdoor activities
- Have a setting where you have to fill out the forming form before you can access your phone

### Notes
