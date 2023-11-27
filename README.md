# Cybersecurity Escape Room

This was created by Steven Hatting as part of a final project for Advanced Enterprise Security - one of the M-IT courses at New Mexico State University.

## What is Cybersecurity Training?

Cybersecurity training is a special training whose purpose is to "bring awareness to certain security exploits and reporting possible exploits when discovered" (Alvero, K.M. (2021, Aug 27). What Role do Humans Play in Ensuring Cybersecurity? ISACA. https://www.isaca.org/resources/isaca-journal/issues/2021/volume-5/what-role-do-humans-play-in-ensuring-cybersecurity).

In order for a cybersecurity training to be important, it must fit 3 specific guidelines:
1. Provide an understanding of the business as a whole and how each employee fits into it.
2. Bring awareness of certain types of cyberattacks or potential pitfalls.
3. Introduce awareness of policies and procedures (either implemented by a government or the organization) related to access to databases, password management, updates which should be installed, programs that should be installed, reporting suspicious activity, etc.

Some of the pitfalls begin to occur when employees are treating these training sessions as something to be done but when attending, their brains turn off. Usually this is because the seminars are too long, boring, repetitive, or too technical (particularly if dealing with non-technical staff). Therefore, this particular kind of training is meant to increase user engagement. It can be implemented offline in-person if trainees have Internet access or online.

## Why is Cybersecurity Training Important?

Did you know that in 2023, 74% of cyberattacks had a human element (e.g. social engineering attacks, errors, or misuse)? (Verizon. (2023). 2023 Data Breach Investigations Report. Verizon Business. https://www.verizon.com/business/resources/reports/dbir/)

Did you also know that 33% of companies don't provide training to remote employees? (CIS. (2022, June 22). 4 Reasons Why Security Awareness Training Is Important. CIS. https://www.cisecurity.org/insights/blog/4-reasons-why-security-awareness-training-is-important)

In addition to that, 18% of workers working remotely are not secure! (HSE. (2023, January 12). 1 IN 3 ORGANIZATIONS DOES NOT PROVIDE ANY CYBERSECURITY TRAINING TO REMOTE WORKERS DESPITE A MAJORITY OF EMPLOYEES HAVING ACCESS TO CRITICAL DATA. Hornetsecurity. https://www.hornetsecurity.com/en/press-releases/1-in-3-organizations-does-not-provide-any-cybersecurity-training-to-remote-workers/)

Implementing a cybersecurity training program is more important now more than ever. By increasing the awareness of an organization's employees in various types of cyberattacks and also types of misuse of technology, the likelihood of falling for such kinds of attack would, of course, reduce. However, as mentioned above, many of these trainings are often long, drawn-out, and boring or they offer no real useful information at all. With these various tasks, it is hoped that a trainee's liklihood of misusing technology or falling for some kind of social engineering attack (e.g. phishing) would reduce.

## How to Deploy the Password Button

For each task on each webpage, a password must be chosen by you. After determining the password, replace the "TODO:" string of text to the password that the trainee must enter in order to continue on to the next puzzle. After the correct password is entered, a special button will appear which the user can click to be transferred to the next. You will need to add this code to every page which a puzzle is hosted. If you are using Google Sites, you can just copy and paste the code into the widget "Embed from the Web" and then choose "Embed code." It should also be noted that the password that is input by the trainee or you as the trainer is case sensitive. For example, if I discover that the password is "MASTER" but I type in "master" or "Master," the button will not appear. This should be made clear to participants if you feel it necessary.

## How to Deploy Phishing Task

The code from the phishing.html can be copied and pasted into the embed module (if you are using Google Sites) or can be deployed as its own standalone webpage. You just need to find the different "TODO:" in each of the emails. These can be changed to go to actual additional websites which you will need to create which can include hints about the password, or they can be changed to the passwords themselves in the "title" part. This way, when the trainee hovers their cursor over the hyperlinked text, they will see the password or its hint.

## How to Deploy Password Task

The password task uses a Caesar cipher in Javascript in order to change words and phrases into nonsense. The goal of the user is to decipher the different nonsense passwords, which you must create yourself, in order to decipher what the actual password is. I have found it useful to have some common passwords like "abc123" on one side sprinkled in with a few clues that have been ciphered using the already deployed embedded module. I wouldn't recommend having more than 8 or 9 fake passwords like that in your list. Then take your password that you've chosen and think of some descriptors for it. For example, it can be "two words," "no numbers," etc. Cipher these clues and then cipher your password. Then throw them into the list that you have already started compiling. If it gets to be too many, take out the distractors. I also don't recommend using more than 3 words for the ciphered clues or passwords.

Also, please note that the cipher which I have included does not change any numbers or symbols. These remain the same, so if you want to use numbers in your hints, I recommend using them written out verbally (e.g. "one" instead of "1").

## Incident Response Awareness

It might be a good idea to add an additional puzzle task in which the trainees must answer questions related to IR policies held by the organization. This can be in the form of a Google Form. For example, one might add questions like "What types of incidents are covered in the policy?" or "Who is responsible for each step in the incident response process?" Making your questions generic but about your company's policies will increase the awareness of your employees. Once the form is submitted, instead of using the default, "Thank you! Your response has been recorded," you can replace it with "Thank you! Your password is:"

## Social Engineering Tech Support

In my trainings, I also included some kind of tech support bot from ChatGPT. In order to make or use this task, you would need a subscription to ChatGPT plus. Once subscribed, you could make your own GPT and provide it the instructions to never leak the password except in certain circumstances. For example, once the GPT trusts the user, they could leak the password. At that point, the trainee wins, but also learns about how social engineering attacks can work in chats or over the phone. If you would prefer to use mine, you can find my GPT here: https://chat.openai.com/g/g-Q3yITEoJq-guardian-key and the password is "MASTER".

## A Note about Escape Rooms

When it comes to planning an escape room, I have always found it best practice to plan things regressively - that is, start with the end phenomena and move towards the beginning. This enables better planning and makes the process move a little bit faster than if you start with planning at the beginning. For example, if you want the trainee to learn about phishing, it's better to start with choosing which password or passphrase will be used. Then, decide how you will sprinkle hints into the task. Then as you create the task, think about distractors you can add in order to make it more difficult for the trainee. More distractors will mean that the difficulty will increase, so use these distractors sparingly.

## Conclusion

In the end, make sure that the skill or principle you want your trainees to know are clear in the task that you are making them do. For example, if you make the tasks too difficult by adding lots of distractors, it could end up resulting in trainees giving up as the tasks would be too difficult. If you focus on just keeping the tasks from point A to point B with only 1 or 2 distractors, it will make it easier for the trainees and they will be able to focus on the end phenomena - in this case phishing.

During the discussion period after trainees finish the task, you can ask them to compare what they did during the puzzle with real life and maybe foster more discussion on how to prevent whatever the topic or main idea is for the task.
