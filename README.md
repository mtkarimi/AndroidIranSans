# AndroidIranSans
dedicated project to use your licensed iran sans fonts easily in android versions api 7+
easily put these files into your project and use
  
     /**
     * /////----------- IRAN SANS 4.2 FONTS -----------\\\\\
     * 1 IRANSansMobile_UltraLight
     * 2 IRANSansMobile_Light
     * 3 IRANSansMobile
     * 4 IRANSansMobile_Medium
     * 5 IRANSansMobile_Bold
     */
     
     IranSansWrapper.GetSansTypeFace(context, Type)
     
     exp:
     View.setTypeFace(IranSansWrapper.GetSansTypeFace(this, 3));
     
     
     And to make sure all the text and numbers renders in persian you can use
     this line of code and you can support persian in all versions of androids Api 3+
        // pass a String instead of str
          IranSansWrapper.GetPersianFull(str);
          
          //use it if you want to show some english numbers too
          IranSansWrapper.GetPersian(str);
          
          View.setText(IranSansWrapper.GetPersian(سلام));
        

put this jar into your libs forlder and then import it.
you can even change the source codes inside jar.
import mt.karimi.iransans.IranSansWrapper;
