# RemindTextView
textView提示框，可自定义标题及风格


使用方法：把TextView文件夹拖到项目里面即可
依赖SVProgressHUD 和UITextView+Placeholder

实例：
 [RemindTextView showWithController:self title:@"提示" warning:@"请输入信息" limit:100 text:nil cancelBtnTitle:@"不填写继续" sureBtnTitle:nil andRequestDataBlock:^(NSString *text) {
        NSLog(@"textView:%@",text);
    }];
    
    
    
