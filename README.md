# Number-Plate-Detection
Reconstruct the old project - Number Plate Detection using Opencv Library.

So , I build a Number Plate Detection using Opencv Library ( Machine Learning )

![number1](https://user-images.githubusercontent.com/72247049/107149549-2bb55800-697f-11eb-866c-1a7ff65cfd99.jpg)

and also add some more interesting thing that is to save the number plate which is detect by my model.

![2021-02-07 18-06-39 - Copy_Trim_Moment(2)](https://user-images.githubusercontent.com/72247049/107149655-ce6dd680-697f-11eb-92c1-57f24ef99dd9.jpg)

you can check the which number plate it will be detect so just create a new directory "Resources" and save it.

if cv2.waitKey(1) & 0xFF == ord('s'):

        cv2.imwrite("Resources/Scanned/NoPlate_"+str(count)+".jpg",imgRoi)
        
        cv2.rectangle(img,(0,200),(640,300),(0,255,0),cv2.FILLED)
        
        cv2.putText(img,"Scan Saved",(150,265),cv2.FONT_HERSHEY_DUPLEX,
        
        2,(0,0,255),2)
        
        cv2.imshow("Result",img)
        
        cv2.waitKey(500)
        
        count +=1

![2021-02-07 18-06-39 - Copy_Trim_Moment(3)](https://user-images.githubusercontent.com/72247049/107149745-6bc90a80-6980-11eb-9c55-1e3be698f9fd.jpg)
