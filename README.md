# IssueForEverything

**Appium:** https://github.com/appium/appium/issues/15261

**Flutter:**  
**1.** Muốn sử dụng async trong Widget build nhưng [lời khuyên từ StackOverflow](https://stackoverflow.com/questions/53800662/how-do-i-call-async-property-in-widget-build-method) là **không nên**, lời khuyên là dùng code async trong iniState rồi setState để cập nhật lại nhưng không đưa ra code ví dụ, [đây](https://chat.openai.com/share/673e34d1-5096-4e8b-a415-0c90ce4a20c3) là ví dụ từ ChatGPT  
**2.** Để từ thằng con yêu cầu thằng cha setState để refresh lại dữ liệu đã thêm hay cho mục đích gì đó thì có vẻ dễ dang, nhưng từ thằng con nằm trong thằng cha B mà yêu cầu thằng cha A (thằng cha B là con của thằng cha A) refresh lại thì hơi phức tạp, tham khảo [Cách của ChatGPT](https://chat.openai.com/share/a362e996-f45d-4f65-bd52-cb8d20a8bfc5) xử lý, trong quá trình làm [Project Flutter](https://github.com/HelloWorldDC/Android/tree/main/Flutter/lam_quen_flutter) thấy hơi phức tạp nên đã dùng thư viện Provider để quản lý trạng thái. 
