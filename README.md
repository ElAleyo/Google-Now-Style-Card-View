Google-Now-Style-Card-View
==========================
Google Search for Android has been updated to take advantage of various new Google Now cards, including one for live TV. 

This project clones the card inserting animation, card exchange animation and provides UITableView alike APIs for data sourcing and delegating.

Add 'Card View' (Dir) to your project and start to use RSCardsView.

    RSCardsView *view = [[[RSCardsView alloc] initWithFrame:[UIScreen mainScreen].applicationFrame] autorelease];
    view.delegate = self;
    view.dataSource = self;
    view.animationStyle = RSCardsViewAnimationStyleExchange; // or RSCardsViewAnimationStyleDrop
    self.view = view;

You should implement your own card and card view, open sample to see lot more.

[![ScreenShot](https://raw.github.com/GabLeRoux/WebMole/master/ressources/WebMole_Youtube_Video.png)](http://player.youku.com/player.php/sid/XNTc4MDUyODY0/v.swf)
