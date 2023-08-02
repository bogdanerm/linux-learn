tr [:upper:] [:lower:] < items.txt > output.txt 
cat /proc/499903/environ | tr [:cntrl:] '\n'
cat /proc/499903/environ | tr '\x00' '\n'
