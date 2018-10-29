
`MXActionSheet` is an easy actionSheet something like weChat to use !

## Screenshots

One bottom title | Two bottom titles | Destructive titles | More than two bottom titles
---|----|----|-----
<image src="https://user-images.githubusercontent.com/38175174/47633246-1fc77280-db88-11e8-9322-cb07ea853b21.gif" width="250">|<image src="https://user-images.githubusercontent.com/38175174/47633290-4ab1c680-db88-11e8-88e1-cfae8f780d75.gif" width="250">|<image src="https://user-images.githubusercontent.com/38175174/47633321-6917c200-db88-11e8-8736-7cbf7562efc7.gif" width="250"> | <image src="https://user-images.githubusercontent.com/38175174/47633402-bbf17980-db88-11e8-8f61-0ae2fbdd90e4.gif" width="250">



## How To Use

### One bottom title

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:nil otherButtonTitles:@[@"title 1st"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```
### Two bottom titles

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:nil otherButtonTitles:@[@"title 1st", @"title 2nd"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```
### Destructive titles

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:@"destructive titles" otherButtonTitles:@[@"title 1st", @"title 2nd"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```
### More than two bottom titles

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:nil otherButtonTitles:@[@"title 1st", @"title 2nd", @"title 3th"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```

<br/>
##中文介绍

`MXActionSheet` 是一个从底部上来的弹窗控件，仿微信里操作一样!

## 屏幕截图

一个底部标题 | 两个底部标题 | 删除底部标题 | 超过两个底部标题
---|----|----|-----
<image src="https://user-images.githubusercontent.com/17949980/35078903-90963830-fc3f-11e7-8184-7438aaaa1657.gif" width="250">|<image src="https://user-images.githubusercontent.com/17949980/35079532-23b47e58-fc43-11e7-8a75-21eaeac65344.gif" width="250">|<image src="https://user-images.githubusercontent.com/17949980/35079615-a73f41b8-fc43-11e7-9640-56ca24e0dc6e.gif" width="250"> | <image src="https://user-images.githubusercontent.com/17949980/35079974-b3bebe1c-fc45-11e7-842a-22296ecfcc1b.gif" width="250">



## 如何使用

### 一个底部标题

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:nil otherButtonTitles:@[@"title 1st"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```
### 两个底部标题

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:nil otherButtonTitles:@[@"title 1st", @"title 2nd"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```
### 删除底部标题

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:@"destructive titles" otherButtonTitles:@[@"title 1st", @"title 2nd"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```
### 超过两个底部标题

``` Objective-C
[MXActionSheet showWithTitle:@"MXActionSheet Supporting bellow Styles" cancelButtonTitle:@"cancel" destructiveButtonTitle:nil otherButtonTitles:@[@"title 1st", @"title 2nd", @"title 3th"] selectedBlock:^(NSInteger index) {
        NSLog(@"------> index: %ld", index);
    }];
```



