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
| citizen | 자신의 증상을 입력 | |
| system | 증상과 관련된 모든 병명을 필터링해서 보여주기 | UC-4: SearchDieases |
| citizen | 자세히 보고 싶은 질병 선택하기 | UC-4: SearchDieases |
| system | 선택된 질병의 정의, 원인, 증상, 진단, 치료, 경과, 주의사항, 진료과 정보 보여주기 | UC-4: SearchDieases |
| citizen | 진료를 받을지 여부 선택하기 | UC-5: FindHospital |
| citizen | 진료를 대면으로 받을지 비대면으로 받을지 선택하기 | UC-5: FindHospital |
| locationSensor | 사용자의 현재 위치가 어디인지 알아내기 | UC-5: FindHospital |
| system | 지도에서 사용자의 위치와 진료과 정보를 바탕으로 병원 검색 후 보여주기 | UC-5: FindHospital |
| system | 의사 데이터베이스에서 진료과 정보를 바탕으로 필터링 | UC-6: FindClinic |

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
