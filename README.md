# YXDFirstRemindView
好多应用在进入某个页面的时候会有引导提示，无非是几张图片切换一下，完全是重复的低级劳动。献上简单demo一枚。

需要做的：

-(void)viewDidAppear:(BOOL)animated {
    [super viewDidAppear:animated];
    [YXDFirstRemindView showRemindViewWithImageNames:@[@"1",@"2",@"3"] key:@"ViewController"];
}
