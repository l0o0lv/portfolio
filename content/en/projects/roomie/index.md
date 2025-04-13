---
title: Roomie
summary: Jan. 2023 - Feb. 2024
date: 2024-09-19
type: docs
math: false
---

### Overview

'Roomie' is a mobile-based roommate matching platform.

Rebuilt and **deployed** the existing '[FindRoommate](../findRoommate)' project from scratch to fit the mobile environment.


- Deployment: [One Store](https://m.onestore.co.kr/mobilepoc/apps/appsDetail.omp?prodId=0000774374) | [App Store](https://apps.apple.com/us/app/roomie/id6477328689)
- Documentation: [{{< icon name="hero/document" >}}](Roomie.pdf)
- Code: [{{< icon name="brands/github" >}}](https://github.com/rkdbq/Roomie-v2) 
- Technologies Used: {{< icon name="devicon/dart" >}} | {{< icon name="devicon/flutter" >}} | {{< icon name="devicon/firebase" >}}
- Dev. Environment: {{< icon name="devicon/android" >}} | {{< icon name="devicon/apple" >}}
- Dev. Period: Jan. 2023 - Feb. 2024

### <u>My Contributions</u>

1. Requirements Analysis
    ![screen reader text](설문조사.png)
    - Conducted two surveys to quantitatively confirm user requirements.
    - Collected 138 responses in the first survey in Jan. 2023.
    - Collected 129 responses in the second survey in Jul. 2023.
2. Improved Recommendation System
    ![screen reader text](추천시스템.png)
    - Enhanced user convenience by switching from manual filter adjustments to Content-based Filtering.
    - Adopted Content-based Filtering as it does not require data from other users, making it suitable for the initial service launch.
    - Adjusted the weights of each item based on user feedback to recommend better profiles.
3. Chat
    ![screen reader text](채팅.png)
    - Transitioned from the existing socket communication method to an asynchronous method using Flutter's Stream, enabling asynchronous communication.

### Limitations

1. Lack of Maintenance
    - Failed to secure a sufficient user base due to the overhaul of the existing dormitory system.
2. Additional Features
    - Need to add detailed features such as multi-language support.