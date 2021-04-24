# Use Cases
- Use Cases의 Full version은 여기[(Link)](https://www.notion.so/b77ac0d510e24f19b4473dbf6c786e0a?v=7ab95d34d295457bba9eb7007ecbe7ea)서 확인할 수 있습니다. **(Notion Pages)**

## Deriving Use Cases from System Requirements
| **Actor** | **Actor's Goal** | **Use Case Name** |
|:--------|:--------|:--------|
| Patient | Write a chat to send to doctor. And also select doctors/conversation which want to show. | UC-1: Clinic<br>UC-2: ManageClinic |
| Doctor | Write a chat to send to patient. And also select patients/conversation which want to show. | UC-1: Clinic<br>UC-2: ManageClinic |
| Server | Connect patient and doctor in on-line. | UC-1: Clinic |
| Interface | Show the chatting room in Real-Time on the participant's screen. And also some buttons. | UC-1: Clinic<br>UC-2: ManageClinic<br>UC-3: MatchClinic |
| Database | Save doctor's information, conversation history(chatting). | UC-1: Clinic<br>UC-2: ManageClinic<br>UC-3: MatchClinic |
| Database | Have blackList information and update on every request. | UC-3: MatchClinic |
| Interface | Have some interface elements such as buttons to add someone in blacklist. | UC-3: MatchClinic |
| System | Filter all disease names associated with symptoms | UC-4: SearchDieases |
| Patient and general user | Choose a disease user want to see more about | UC-4: SearchDieases |
| System | Show definitions, causes, symptoms, diagnosis, treatment, progress, precautions, medical information | UC-4: SearchDieases |
| Patient and general user | Choosing whether to get medical treatment | UC-5: FindHospital |
| Patient and general user | Choosing whether to get treatment offline or online | UC-5: FindHospital |
| LocationSensor | Get user's current location | UC-5: FindHospital |
| System | Search and show the hospital based on your location and medical department on the map | UC-5: FindHospital |
| System | Filter from doctor's database based on medical department | UC-6: FindClinic |
| System | Show profile based on filtered data of doctor's list| UC-6: FindClinic |

## Detailed Use Cases
- Link에서 세부 명세서를 확인할 수 있습니다. **(Notion)**

| **Identifier** | **Use Case Name** | **Detail (Notion)** |
|:--------:|:--------:|:--------:|
| UC-1 | Clinic | [Link](https://www.notion.so/Use-Case-UC-1-901ddf7bf72f42e3aa2fa094bcda7cc5) |
| UC-2 | ManageClinic | [Link](https://www.notion.so/Use-Case-UC-2-a2452e49b2a34dd796fcd8ae861e914e) |
| UC-3 | MatchClinic | [Link](https://www.notion.so/Use-Case-UC-3-f31e0eb76ca6432abe1b659710da98ef) |
| UC-4 | SearchDisease | [Link](https://www.notion.so/Use-Case-UC-4-3b448dfa06234f00adc5bf24c8ebd43b) |
| UC-5 | FindClinic | [Link](https://www.notion.so/Use-Case-UC-5-e8b8f8d4acf74f3495e8d751db21afe7) |
| UC-6 | FindDoctor | [Link](https://www.notion.so/Use-Case-UC-6-2736728fdc024b8dbfdaefb5a84cf303) |
| UC-7 | AddUser | [Link](https://www.notion.so/Use-Case-UC-7-f7c541dca1e34b079b60b5ebebdad7bc) |
| UC-8 | ConditionCheck | [Link](https://www.notion.so/Use-Case-UC-8-366ab650995b499f906f8496a8c98921) |
| UC-9 | LifePattern | [Link](https://www.notion.so/Use-Case-UC-9-564e91bf8d774b31b7af002f9e10a9e9) |
| UC-10 | Disease Management | [Link](https://www.notion.so/Use-Case-UC-10-1155141a58e24cbdb2a00bab93926d18) |
