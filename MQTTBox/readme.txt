尤其要注意的是 在配置mqtt client时 默认勾选了 append_timestamp to mqtt client id 以及 mqtt_client_id是随机产生的
如果指定client id 想要制造相同client id造成的重复互相断连的情况 需要将默认勾选去掉 并且自己指定client id