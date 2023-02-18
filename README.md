# vpn_manager_with_flask
 
## create user by set count.
 http://127.0.0.1:5000/create 
 
                    @  item_count=1
                    @  expire=30
                    @  trafiic=30
                    @  inbound_id=1
                    @  limit_ip_count=1
                    @  title=Speedoooooooooooooo


## remove user by id
http://127.0.0.1:5000/remove 

                    #  id=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
                    


## get all user_item_count 

http://127.0.0.1:5000/user_item_count



## chnage Expire Date by user_id

http://127.0.0.1:5000/change_expire_date.

                    # id=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
                    # expire=20



## chnage total traffic by user_id                    

http://127.0.0.1:5000/change_total_traffics

                    # id=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
                    # total_traffics=1



## change ip limit by user_id        

http://127.0.0.1:5000/chnage_ip_limit

                    # id=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
                    # ip_limit=20
                    
                    
