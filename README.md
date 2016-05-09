# android-complicated-problems

origin : http://konifar-zatsu.hatenadiary.jp/entry/2016/05/05/002128

# Complicated problems

[ja](README_ja.md)

1. Continue loading data and display them on a screen (ex. RecyclerView, ListView and more) even if Activity or Fragment is recreated by a screen rotation.
2. Cancel loading data when an Activity or Fragment is paused or stopped.
3. Click button such as Like Button then immediately open next Activity or Fragment. It will destroy the button but should continue the handling.
4. Allow to retry if load of content failed..
5. Open the screen in an off-line mode. the screen require request to API.
6. Show rectangle ad if search result is empty. Otherwise show banner ad on footer.
7. Integrate multiple request. e.g. Loading a content of HeaderView and a content of RecyclerView. Both request wait for each other.
8. Display a native ad in second and eighth in the list. The ad should preloaded.
9. When send message in message form, show result before end of the request.
10. Allow to retry if send of message failed. It is necessary to solve this problem with No 9.
11. Load optimized image in each situation. WiFi, 3G, narrow band and more.
12. Preload content if connected to WiFi.
