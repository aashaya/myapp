#### Begin Robo Reception Call by calling  561-559-6410

#### Booking  an emergency appointment as a new patient, with the user provided date and time slot available.

#### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: User initiates the conversation with a request to "Book appointment."
   - **Expected Response**: RoboReception introduces itself, offers help with appointments, and inquires how it can assist further.

2. **Identify as New Patient**
   - **Action**: Respond with "new."
   - **Expected Response**: RoboReception  thanks the user and proceeds to collect necessary information for booking.

3. **Provide Phone Number**
   - **Action**: Enter "###-###-####" when asked for the phone number.
   - **Expected Response**: RoboReception  repeats the phone number back to confirm its accuracy.

4. **Confirm Phone Number**
   - **Action**: Confirm the accuracy of the phone number with "yes."
   - **Expected Response**: RoboReception  acknowledges the confirmation and asks for the patient's first name.

5. **Provide Patient's First Name**
   - **Action**: Respond with "John."
   - **Expected Response**: RoboReception  requests the patient's last name.

6. **Provide Patient's Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: RoboReception  inquires about the patient's date of birth.

7. **Provide Date of Birth**
   - **Action**: Enter "Oct 2 1947."
   - **Expected Response**: RoboReception  repeats the date of birth for confirmation.

8. **Confirm Date of Birth**
   - **Action**: Confirm the date of birth with "yes."
   - **Expected Response**: RoboReception  acknowledges and registers the patient in the system.

9. **Select Appointment Type**
   - **Action**: Specify the type of appointment needed as "emergency."
   - **Expected Response**: RoboReception  confirms the appointment type and asks for a preferred date.

10. **Specify Appointment Date**
    - **Action**: Respond with "March 18."
    - **Expected Response**: RoboReception  repeats the date for confirmation.

11. **Confirm Date and Specify Time**
    - **Action**: Confirm the date is correct and specify the time as "11 am."
    - **Expected Response**: RoboReception  confirms the time and summarizes the appointment details.

12. **Confirm Appointment Details**
    - **Action**: Agree to the summarized appointment details with "yes."
    - **Expected Response**: RoboReception  checks availability and proceeds to book the appointment.

13. **Appointment Booking Confirmation**
    - **Action**: Await confirmation of the booking.
    - **Expected Response**: RoboReception  confirms the appointment has been booked and explains the SMS verification process.

14. **Conclude Interaction**
    - **Action**: Respond with "no" when asked if there's anything else RoboReception  can assist with.
    - **Expected Response**: RoboReception  thanks the user, wishes them a great day, and ends the conversation.


#### Booking  a consult appointment as a new patient, with the user provided time unavailable but other slots available on same date

#### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: Send the message "Book appointment."
   - **Expected Response**: RoboReception should offer assistance in scheduling an appointment and inquire whether the user is a new or returning patient.

2. **Identify as New Patient**
   - **Action**: Respond with "new."
   - **Expected Response**: RoboReception should acknowledge the user as a new patient and request their phone number, including the area code.

3. **Provide Phone Number**
   - **Action**: Enter "###-###-####."
   - **Expected Response**: RoboReception should repeat the phone number back to confirm its accuracy.

4. **Confirm Phone Number**
   - **Action**: Confirm with "yes."
   - **Expected Response**: RoboReception should thank the user and proceed to ask for the patient's first name.

5. **Provide Patient's First Name**
   - **Action**: Respond with "John."
   - **Expected Response**: RoboReception should request the patient's last name.

6. **Provide Patient's Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: RoboReception should ask for the patient's date of birth.

7. **Provide Date of Birth**
   - **Action**: Enter "Oct 7 1947."
   - **Expected Response**: RoboReception should confirm the date of birth by repeating it back.

8. **Confirm Date of Birth**
   - **Action**: Confirm with "yes."
   - **Expected Response**: RoboReceptionshould indicate that it is registering the user in the system.

9. **Select Appointment Type**
   - **Action**: Request "Aligners consult."
   - **Expected Response**: RoboReceptionshould confirm the appointment type as "Aligners Consult."

10. **Specify Appointment Date**
    - **Action**: Indicate "March 18."
    - **Expected Response**: RoboReceptionshould confirm the chosen date.

11. **Specify Appointment Time**
    - **Action**: Suggest "7 am."
    - **Expected Response**: RoboReceptionshould ask for confirmation of the proposed time.

12. **Handle No Availability and Offer Alternative**
    - **Action**: Confirm the time with "yes."
    - **Expected Response**: RoboReceptionshould inform the user that the requested time is unavailable but offer an alternative time slot.

13. **Accept Alternative Time Slot**
    - **Action**: Agree with "yes."
    - **Expected Response**: RoboReceptionshould confirm that it is checking the availability in the schedule.

14. **Appointment Confirmation**
    - **Action**: Wait for the chatbot's response.
    - **Expected Response**: RoboReceptionshould confirm the booking of the appointment and explain the SMS confirmation process.

15. **Conclude Interaction**
    - **Action**: Indicate that no further assistance is needed.
    - **Expected Response**: RoboReceptionshould thank the user for their inquiry and say goodbye.

#### New patient booking an emergency appointment when there is no slots open on user provided date. Looking for next available appointment and accepting the first offered slot:

#### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: Send the message "Book Appointment."
   - **Expected Response**: "Ok great, I would be happy to help you schedule an appointment. I just need to ask you a few questions. Are you a New Patient, or a Returning patient at True Dental Care?"

2. **Identify as New Patient**
   - **Action**: Respond with "New Patient."
   - **Expected Response**: "Thank you! Please say your phone number starting with the area code?"

3. **Provide Phone Number**
   - **Action**: Say "Phone Number".
   - **Expected Response**: "I wrote down {Phone Number} is this correct?"

4. **Confirm Phone Number**
   - **Action**: Respond with "Thank you!"
   - **Expected Response**: "Can you please say the patient's first name?"

5. **Provide First Name**
   - **Action**: Say "John."
   - **Expected Response**: "Please say the patient's last name?"

6. **Provide Last Name**
   - **Action**: Say "Cena."
   - **Expected Response**: "What is the patient's date of birth?"

7. **Provide Date of Birth**
   - **Action**: Say "June 1 1947."
   - **Expected Response**: "The date of birth I wrote down is 1947-06-01 ? is this correct?"

8. **Confirm Date of Birth**
   - **Action**: Respond with "yes."
   - **Expected Response**: "Thank you! Please give me a few seconds... Thank you for waiting. I've registered you in our system!"

9. **Specify Appointment Type**
   - **Action**: Say "cleaning."
   - **Expected Response**: "I wrote down Exam and or Cleaning is this correct?"

10. **Confirm Appointment Type**
    - **Action**: Respond with "yes."
    - **Expected Response**: "What date would you like to come in?"

11. **Specify Appointment Date**
    - **Action**: Say "March 15."
    - **Expected Response**: "The date I wrote down is 2024-03-15 ? is this correct?"

12. **Confirm Appointment Date**
    - **Action**: Respond with "yes."
    - **Expected Response**: "What time would you like to come in?"

13. **Specify Appointment Time**
    - **Action**: Say "10 am."
    - **Expected Response**: "Can you please confirm, you said at 10:00 AM? Is this correct?"

14. **Confirm Appointment Time**
    - **Action**: Respond with "yes."
    - **Expected Response**: "Sorry. I couldn't find any opening on 2024-03-15. Would you like me to check for the next available appointment for you?"

15. **Request Next Available Appointment**
    - **Action**: Respond with "yes."
    - **Expected Response**: "Okay. I've next opening on 2024-03-18 at 08:00 AM with Bruce Bently. Would you like to book it?"

16. **Book Appointment**
    - **Action**: Respond with "yes."
    - **Expected Response**: "Your appointment has been booked. Thank you for booking. You will receive two SMS text messages..."

17. **Conclude Interaction**
    - **Action**: Say "no" when asked if there's anything else the assistant can help with.
    - **Expected Response**: "Thank you for calling True Dental Care. Have a great day! Good Bye!”


#### New patient booking an emergency appointment when there is no slots open on user provided date. Looking for next available appointment and accepting other slots offered:

#### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: Send the message "book appointment."
   - **Expected Response**: The chatbot should offer assistance in scheduling an appointment and inquire whether the user is a new or returning patient.

2. **Identify as New Patient**
   - **Action**: Respond with "new."
   - **Expected Response**: The chatbot should acknowledge the user as a new patient and request their phone number, including the area code.

3. **Provide Phone Number**
   - **Action**: Enter “###-###-####"
   - **Expected Response**: The chatbot should repeat the phone number back to confirm its accuracy.

4. **Confirm Phone Number**
   - **Action**: Confirm with "yes."
   - **Expected Response**: The chatbot should thank the user and proceed to ask for the patient's first name.

5. **Provide First Name**
   - **Action**: Say "John."
   - **Expected Response**: The chatbot should request the patient's last name.

6. **Provide Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: The chatbot should ask for the patient's date of birth.

7. **Provide Date of Birth**
   - **Action**: Enter "oct 10 1947."
   - **Expected Response**: The chatbot should confirm the date of birth by repeating it back.

8. **Confirm Date of Birth**
   - **Action**: Respond with "yes."
   - **Expected Response**: The chatbot should indicate that it is registering the user in the system.

9. **Specify Appointment Type**
   - **Action**: Request an "emergency" appointment.
   - **Expected Response**: The chatbot should confirm the appointment type as Emergency.

10. **Specify Appointment Date**
    - **Action**: Indicate "March 18."
    - **Expected Response**: The chatbot should confirm the chosen date.

11. **Specify Appointment Time**
    - **Action**: Suggest "7 am."
    - **Expected Response**: The chatbot should ask for confirmation of the proposed time.

12. **Respond to First Time Slot Offer**
    - **Action**: Respond with "no" to the 08:30 AM slot.
    - **Expected Response**: The chatbot should offer the next available slot at 09:00 AM.

13. **Respond to Second Time Slot Offer**
    - **Action**: Respond with "no" to the 09:00 AM slot.
    - **Expected Response**: The chatbot should offer the next available slot at 09:30 AM.

14. **Respond to Third Time Slot Offer**
    - **Action**: Respond with "no" to the 09:30 AM slot.
    - **Expected Response**: The chatbot should offer the next available slot at 10:00 AM.

15. **Accept Final Time Slot Offer**
    - **Action**: Respond with "yes" to the 10:00 AM slot.
    - **Expected Response**: The chatbot should confirm the booking of the appointment.

16. **Conclude Interaction**
    - **Action**: Say "no" when asked if there's anything else the assistant can help with.
    - **Expected Response**: The chatbot should thank the user and end the conversation with a goodbye message.


#### New patient booking a cleaning appointment as soon as possible and accepting the first offered slot:

#### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: Send the message "Book appointment."
   - **Expected Response**: The chatbot should offer assistance in scheduling an appointment and inquire whether the user is a new or returning patient.

2. **Identify as New Patient**
   - **Action**: Respond with "new."
   - **Expected Response**: The chatbot should acknowledge the user as a new patient and request their phone number, including the area code.

3. **Provide Phone Number**
   - **Action**: Enter "###-###-####."
   - **Expected Response**: The chatbot should repeat the phone number back to confirm its accuracy.

4. **Confirm Phone Number**
   - **Action**: Confirm with "yes."
   - **Expected Response**: The chatbot should thank the user and proceed to ask for the patient's first name.

5. **Provide First Name**
   - **Action**: Say "John."
   - **Expected Response**: The chatbot should request the patient's last name.

6. **Provide Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: The chatbot should ask for the patient's date of birth.

7. **Provide Date of Birth**
   - **Action**: Enter "oct 11 1947."
   - **Expected Response**: The chatbot should confirm the date of birth by repeating it back.

8. **Confirm Date of Birth**
   - **Action**: Respond with "yes."
   - **Expected Response**: The chatbot should indicate that it is registering the user in the system.

9. **Specify Appointment Type**
   - **Action**: Request a "cleaning" appointment.
   - **Expected Response**: The chatbot should confirm the appointment type as Exam and/or Cleaning.

10. **Request Appointment Date**
    - **Action**: Say "as soon as possible."
    - **Expected Response**: The chatbot should indicate it will check for the next available slot.

11. **Accept Offered Slot**
    - **Action**: Respond with "yes" to the offered slot on 2024-03-18 at 09:30 AM.
    - **Expected Response**: The chatbot should confirm the booking of the appointment.

12. **Conclude Interaction**
    - **Action**: Say "no" when asked if there's anything else the assistant can help with.
    - **Expected Response**: The chatbot should thank the user and end the conversation with a goodbye message.


#### Booking  a cleaning appointment as a new patient, with the user seeking the earliest available slot and accepting other available slots 

#### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: Send the message "Book appointment."
   - **Expected Response**: The chatbot should offer assistance in scheduling an appointment and inquire whether the user is a new or returning patient.

2. **Identify as New Patient**
   - **Action**: Respond with "new."
   - **Expected Response**: The chatbot should acknowledge the user as a new patient and request their phone number, including the area code.

3. **Provide Phone Number**
   - **Action**: Enter "###-###-####."
   - **Expected Response**: The chatbot should repeat the phone number back to confirm its accuracy.

4. **Confirm Phone Number**
   - **Action**: Confirm with "yes."
   - **Expected Response**: The chatbot should thank the user and proceed to ask for the patient's first name.

5. **Provide First Name**
   - **Action**: Say "John."
   - **Expected Response**: The chatbot should request the patient's last name.

6. **Provide Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: The chatbot should ask for the patient's date of birth.

7. **Provide Date of Birth**
   - **Action**: Enter "oct 11 1947."
   - **Expected Response**: The chatbot should confirm the date of birth by repeating it back.

8. **Confirm Date of Birth**
   - **Action**: Respond with "yes."
   - **Expected Response**: The chatbot should indicate that it is registering the user in the system.

9. **Specify Appointment Type**
   - **Action**: Request a "cleaning" appointment.
   - **Expected Response**: The chatbot should confirm the appointment type as Exam and/or Cleaning.

10. **Request Appointment Date**
    - **Action**: Say "as soon as possible."
    - **Expected Response**: The chatbot should indicate it will check for the next available slot and ask the user to hold.

11. **Decline First Offered Slot**
    - **Action**: Respond with "no" to the 09:30 AM slot.
    - **Expected Response**: The chatbot should offer the next available slot at 10:00 AM.

12. **Decline Second Offered Slot**
    - **Action**: Respond with "no" to the 10:00 AM slot.
    - **Expected Response**: The chatbot should offer the next available slot at 10:30 AM.

13. **Accept Third Offered Slot**
    - **Action**: Respond with "yes" to the 10:30 AM slot.
    - **Expected Response**: The chatbot should confirm the booking of the appointment.

14. **Conclude Interaction**
    - **Action**: Say "no" when asked if there's anything else the assistant can help with.
    - **Expected Response**: The chatbot should thank the user and end the conversation with a goodbye message.


#### Test Case: Checking an Appointment

##### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: User initiates the conversation with a request to "check appointment."
   - **Expected Response**: The chatbot offers assistance to check the date and time of the user's next appointment and indicates it needs to collect more information.

2. **Provide Phone Number**
   - **Action**: Enter "###-###-####" when asked for the phone number.
   - **Expected Response**: The chatbot repeats the phone number back to confirm its accuracy.

3. **Confirm Phone Number**
   - **Action**: Confirm the accuracy of the phone number with "yes."
   - **Expected Response**: The chatbot thanks the user and proceeds to ask for the patient's first name.

4. **Provide Patient's First Name**
   - **Action**: Respond with "John."
   - **Expected Response**: The chatbot thanks the user and asks for the patient's last name.

5. **Provide Patient's Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: The chatbot requests the patient's date of birth.

6. **Provide Date of Birth**
   - **Action**: Enter "Oct 10 1947."
   - **Expected Response**: The chatbot thanks the user and confirms the date of birth provided.

7. **Confirm Date of Birth**
   - **Action**: Confirm the date of birth with "yes."
   - **Expected Response**: The chatbot acknowledges and locates the user's record, then informs the user of their scheduled appointment.

8. **Appointment Information Provided**
   - **Action**: Await the appointment details from the chatbot.
   - **Expected Response**: The chatbot confirms that the user has one scheduled appointment on 2024-03-18 at 10:00 AM.

9. **Conclude Interaction**
    - **Action**: Respond with "no" when asked if there's anything else the chatbot can assist with.
    - **Expected Response**: The chatbot thanks the user and ends the conversation.


#### Test Case: Canceling an Appointment

##### Test Steps:

1. **Greeting and Initial Request**
   - **Action**: User initiates the conversation with a request to "cancel appointment."
   - **Expected Response**: The chatbot offers to help cancel an appointment and indicates it needs to collect more information.

2. **Provide Phone Number**
   - **Action**: Enter “###-###-####" when asked for the phone number.
   - **Expected Response**: The chatbot thanks the user and repeats the phone number back to confirm its accuracy.

3. **Confirm Phone Number**
   - **Action**: Confirm the accuracy of the phone number with "yes."
   - **Expected Response**: The chatbot thanks the user and proceeds to ask for the patient's first name.

4. **Provide Patient's First Name**
   - **Action**: Respond with "John."
   - **Expected Response**: The chatbot thanks the user and asks for the patient's last name.

5. **Provide Patient's Last Name**
   - **Action**: Reply with "Cena."
   - **Expected Response**: The chatbot requests the patient's date of birth.

6. **Provide Date of Birth**
   - **Action**: Enter "Oct 2 1947."
   - **Expected Response**: The chatbot thanks the user and confirms the date of birth provided.

7. **Confirm Date of Birth**
   - **Action**: Confirm the date of birth with "yes."
   - **Expected Response**: The chatbot acknowledges, locates the user's appointment record, and confirms the appointment details.

8. **Confirm Cancellation**
   - **Action**: Agree to cancel the appointment by responding with "yes."
   - **Expected Response**: The chatbot confirms that the user's appointment has been cancelled.

9. **Conclude Interaction**
    - **Action**: Respond with "no" when asked if there's anything else the chatbot can assist with.
    - **Expected Response**: The chatbot thanks the user, wishes them a great day, and ends the conversation.

