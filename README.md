# AppDelegate
AppDelegate瘦身
在初始化window的文件中要这么写
  (''') 
    UIWindow * window = [[UIWindow alloc]initWithFrame:[UIScreen mainScreen].bounds]; 
    window.backgroundColor = [UIColor whiteColor];
    [window makeKeyAndVisible];
    [UIApplication sharedApplication].delegate.window = window;
  (''')
