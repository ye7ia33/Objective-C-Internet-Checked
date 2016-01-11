// copy files on ur project and follow this code 
        
        
        InternetChecked *internet =[[InternetChecked alloc] init];
    if (internet.Checked) {
    // if u have internet connection in your device 
    // try To write code . .  and enjoy
    }else {
         UIAlertView* alert;
        alert = [[UIAlertView alloc] initWithTitle:@"Info" message:@"no internet connection " delegate:nil  cancelButtonTitle:@"OK" otherButtonTitles: nil];
        [alert show];
    }
