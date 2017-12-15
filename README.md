# Minimart
 by Kotchanat Yaso and Sdith Meesat

 MINI MART

1.Title :  Minimart using GUI with java

2.Team members : Kotchanat Yaso and Sdith Meesat.

3.Description : select things and calculate price that you have to pay in minimart.

4.Detailed description : 

  - Our application customers can select item that you want to buy from our list.
  
  - Warning menu can pop up in two way. 1. select item but dont add how many do you want 2. cilck minus sign but you dont select item

  - Also the our application can 
                    
                    -When our customers select wrong item they can remove it or change it.
                     
                     -When our customers want more item they can add it to list0.
                     
                     -When our customers want to check bill. Our application can calculate summary and                                                                                         show it on screen.
        Receipt from this application     
        
             -    User comfortable to buy things.
             -    Improve our skill about writing program.
-build commma for sum more than 999

DecimalFormat df = new DecimalFormat("#,###.00");

 public void mouseClicked(java.awt.event.MouseEvent evt) {// keep your line your select 
                tbMouseClicked(evt);
            }
        });
        jScrollPane1.setViewportView(tb);
        if (tb.getColumnModel().getColumnCount() > 0) {
            tb.getColumnModel().getColumn(0).setResizable(false);
            tb.getColumnModel().getColumn(1).setResizable(false);
            tb.getColumnModel().getColumn(2).setResizable(false);
            tb.getColumnModel().getColumn(3).setResizable(false);
        }
