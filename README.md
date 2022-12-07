### Hi there 👋

<!--
**Dm2998/Dm2998** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

#Make sure that the script is reusable (executable in bash shell and importable in iPython3 shell)

def listening_ports(): #listening ports
    command = 'netstat -tulpn'
    subprocess.call(command, shell=True)
    
def disk_usage(): # disk usage
    command = 'df -h'
    subprocess.call(command, shell=True)

def network_interfaces(): #network interfaces
    command = 'ifconfig'
    subprocess.call(command, shell=True)

def routing_table(): # routing table
    command = 'route'
    subprocess.call(command, shell=True)
    
def usage_of_tmp_directory(): # usage of /tmp directory
    command = 'du -h /tmp'
    subprocess.call(command, shell=True)

def empty_files_in_tmp_directory(): # empty files in /tmp directory
    command = 'find /tmp -type f -empty'
    subprocess.call(command, shell=True)

def processes_ids_of_root(): # processes IDs of user 'root'
    command = 'ps -u root -o pid='
    subprocess.call(command, shell=True)

def main(): # main function
    print ("Listening ports: ")
    listening_ports()
    
    print ("Disk usage: ")  #print disk usage 
    disk_usage()
    
    print("Network interfaces: ") #print network interfaces
    network_interfaces()
    
    print("Routing table: ") #print routing table
    routing_table()
    
    print("Usage of /tmp directory: ") #print usage of /tmp directory
    usage_of_tmp_directory()
    
    print("Empty files in /tmp directory: ") #  print empty files in /tmp directory
    empty_files_in_tmp_directory()
    
    print("Processes IDs of user 'root': ")# print processes IDs of user 'root'
    processes_ids_of_root()
    
if __name__ == '__main__':
    main()

