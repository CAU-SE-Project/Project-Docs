# Traceability Matrix
- Use Cases를 Domain Model에 Mapping한 Traceability Matrix입니다.
- 한 Page에 모두 표현할 수 있도록 Row와 Column의 방향을 바꾸었습니다.

| **Use Case** | **UC1** | **UC2** | **UC3** | **UC4** | **UC5** | **UC6** | **UC7** | **UC8** | **UC9** | **UC10** |
|:------------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|
| **PW** | **34** | **13** | **14** | **22** | **17** | **19** | **18** | **8** | **11** | **20** |
| Controller-SS1 | X | | | | | | | | | |
| Request | X | | | | | | | | | |
| ConnectOperator | X | | | | | | | | | |
| DatabaseConnection | X | X | X | | | | | | | |
| Chat | X | X | X | | | | | | | |
| SendOperator | X | | | | | | | | | |
| DisplayOperator | X | X | | | | | | | | |
| AlarmOperator | X | | | | | | | | | |
| Logger | X | | X | | | | | | | |
| Controller-SS2 | | X | | | | | | | | |
| CheckAuth | | X | | | | | | | | |
| ConversationList | | X | | | | | | | | |
| SelectConversation | | X | | | | | | | | |
| Controller-SS3 | | | X | | | | | | | |
| Doctor | X | X | X | | | X | | | | |
| CheckDoctor | | | X | | | | | | | |
| SelectDoctor | | | X | | | | | | | |
| Blacklist | | | X | | | | | | | |
| BlacklistOperator | | | X | | | | | | | |
| CheckSignUp | | | | | | | X | | | |
