README: RPI Admissions Chatbot

Bot Name:rpiadmissions

The RPI Admissions Chatbot is designed to provide answers and guidance to prospective students about admissions processes, programs, scholarships, campus life, and other important details at Rensselaer Polytechnic
Institute. The bot leverages the AIML framework and uses contextual response techniques like star, that, set, get, srai, condition, random, think to create an engaging and dynamic interaction.

Features:
1. Admissions Guidance:
Handles queries about admissions deadlines, application processes, and early decision plans.

3. Campus Insights:
Shares information about campus life, housing options, and student activities.
4. Programs and Scholarships:
Explains available programs and scholarship opportunities, including the prestigious Rensselaer Medal.
5. Interactive and Personalized:
Learns the user's name and favorite subject for a more personalized experience.
Asks follow-up questions to keep the user engaged.
6. Links to Resources:
Directs users to official pages on the RPI admissions website for further details.

Design of the Dialogue Management System:

1.Centralized Information:
Common responses ex. help commands and admissions deadlines are handled through dedicated <category> blocks, and some responses use <srai> for redirecting similar queries.

2.Dynamic Context Handling:
<set> and <get>: Used to capture user inputs like name or favorite subject, allowing responses to be personalized.
<that>: Manages contextual responses based on the bot's previous reply, enabling multi-turn interactions.

3.Fallback Mechanism:
By Default, provides a generic response for unrecognized inputs while encouraging the user to ask about admissions, programs, or campus life.

4.Randomization:
<random>: Offers varied responses for questions like "Why should I choose RPI?" to make conversations feel more natural.
