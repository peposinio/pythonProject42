# pythonProject42



#def malware():

#import socket
#for port in range(0, 65535):
    #serv = socket.socket()
    #serv.setimeout(1)
    #try:
        #print(f"the port {port} is open")
        #serv.bind(("0.0.0.0", port))
        #serv.listen()
        #print("the server is listening")
        #(cs, c_addres) = serv.accept()
        #data = cs.recv(2048).decode()
        #while data != "exit\n":
            #cs.send(input("enter in the command line________").encode())
            #data = cs.recv(2048).decode()
            #print(data)
    #except:
        #print(f"the port {port} is close")

    #cs.close()
    #serv.close()

#malware()
