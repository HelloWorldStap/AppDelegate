# AppDelegate
AppDelegate瘦身
在初始化window的文件中要这么写
  ```) 
    UIWindow * window = [[UIWindow alloc]initWithFrame:[UIScreen mainScreen].bounds]; \n
    window.backgroundColor = [UIColor whiteColor];\n
    [window makeKeyAndVisible];\n
    [UIApplication sharedApplication].delegate.window = window;\n
  ```)
