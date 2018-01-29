# The MINDFUL Project
# https://devpost.com/software/project-eqm85f 


***Inspiration***

We were moved by the stories of the Save Ourselves Breast Cancer organization told at the hackathon. After speaking with a breast cancer survivor, Cass, we learned that may women who undergo the strenuous process often have no one to turn to, as persons with cancer often attempt to put on a brave front, and live "double lives", as Cass put it. We realized that the only healthy way for persons with cancer or other serious illnesses to cope would be to maintain and establish significant personal introspection, through daily reflections and community support.


***What it does***

A patient with breast cancer inputs a journal entry into the website, and the website returns a magnitude and size of emotion that the patient is most likely feeling based on that entry. Ideally, the website would then be able to store this information and process, maintain and analyze any arising patterns, both positive and negative for the patient. For example, a patient with repeated low scores (higher risk of negative thoughts and therefore lower emotional stability) may be advised to seek additional therapies, support groups, or other healthy coping mechanisms. The reading is not based on emotion alone, and can detect the overall tone of a message, perhaps not at all about the patients mood, but rather their ongoing live events, something as simple as seeing their son or as upsetting as losing hair after chemotherapy.


***How we built it***

We implemented the Google Cloud Natural Language Processing API to detect and establish scores and magnitudes of journal entry. To connect the back end API usage with the front end, we used the Flask framework with Python. We used GitHub to host our website and used HTML, CSS, and JavaScript to format and stylize the website.


***Challenges we ran into***

We initially wanted to use Firebase to build a database to determine patterns across scores (mapped long term over weeks, months or years), but felt that as 2nd year students, our experiences were insufficient to fully establish a database. Around 4:00AM, we decided to switch from focusing on Firebase to focusing on a specific API, the Natural Language Processing API. This proved much more efficient and useful, as we can use this information for real time analysis (immediate understanding of the patients cognitive mood, and also long term pattern mapping/tracking)


***Accomplishments that we're proud of***

We are really proud of fully integrating the Google Cloud Platform with the NLP API, as the idea was relatively new and the API works fully functional. The information we are able to extract from the API usage is also very significant to both us and the patient.


***What we learned***

We learned how to format a web application, and how to use the Google Cloud API.


***What's next for project***

We are hoping to turn this project idea into a potential startup idea, charting patients short term and long term thought patterns. We are also hoping to fully enable and establish a functional database to care for all patients in the way they deserve and need. We are also hoping to establish a social function, allowing people to post anonymous journal entries for other cancer patients to view and express thoughts with.
