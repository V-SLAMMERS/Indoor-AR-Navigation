  For the people who are not interested in SLAM ecosystem, we provide simple docker images of ORB SLAM2 and LDSO. We are using LDSO for our indoor AR navigation system, but ORB SLAM2 also can be a good reference of SLAM technology.
  
  Thanks to [HeejoonLee](https://github.com/HeejoonLee), we can easily touch the basic SLAM.
  
  Details about this docker image is uploaded at our official git page, [Thread Through](https://V-SLAMMERS.github.io).
  
  Here, you can find the revision history of Docker images.

---

| Date | Version | Image | Description |
| --- | --- | --- | --- |
| 2022/09/20 | 0.1 | heejoon1130/slam:0.1 | 최초 배포. ORB-SLAM2(Kitti), LDSO(Kitti) 지원. Ubuntu 18.04를 base로 제작. |
| 2022/09/23 | 0.2 | heejoon1130/slam:0.2 | LDSO(euroc) 지원. 데이터셋 선택 인터페이스 추가. |
