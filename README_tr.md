tr [:upper:] [:lower:] < items.txt > output.txt 
cat /proc/499903/environ | tr [:cntrl:] '\n'
cat /proc/499903/environ | tr '\x00' '\n'
echo -en '\x41' | tr '\101' '\102'                                      # - transform from A to B in octal
cat /proc/520152/environ | tr '\000' '\012'                             # - transform from null to newline
