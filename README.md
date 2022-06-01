# EBS_Lab
# Create and attach an EBS volume to an EC2 instance.
Once you login to AWS, click on services at the top of the screen and search for EC2. Click on the result to go to the main dashboard of EC2 service.

![image](https://user-images.githubusercontent.com/103466963/171438988-931a2541-20ec-4b31-a45d-3c0f5f8afaf3.png)

This is the main dashboard of EC2 service. Scroll down and in the left panel click on Volume under Elastic Block Store.

![image](https://user-images.githubusercontent.com/103466963/171439167-fa49460f-a425-422d-83ee-4166eed4d687.png)

You will see the following screen. Here you may or may not see any existing volumes. As I already have an EC2 instance in my account the following listed EBS volume is attached to that existing EC2 instance. To create a new EBS volume click on "Create Volume".

![image](https://user-images.githubusercontent.com/103466963/171439386-dc0e5468-1897-4872-85f5-56fc71b91648.png)


Choose the type of volume that you want to create and specify the disk space that needs to be allocated to the volume. Select the Availability Zone. This should be the same as that of an EC2 instance to which this volume will be attached.

You can skip other fields for now and proceed with "Create Volume"

![image](https://user-images.githubusercontent.com/103466963/171440212-0839be63-8fe4-476d-b0b8-358b8ac0474d.png)

The creation will take some time and once the volume has been created you can see its status as "Available". Once the status of the volume changes to available it can be attached to the desired EC2 instance.

![image](https://user-images.githubusercontent.com/103466963/171440501-1aeaba20-3917-433e-a303-99af2212130d.png)

To attach this EBS volume to an EC2 instance, click on Actions --> Attach Volume.

![image](https://user-images.githubusercontent.com/103466963/171441343-6721f42f-d308-48a1-ba21-eeaa92b6aaca.png)

In the following screen specify the Instance ID of the EC2  instance to which this EBS volume needs to be attached. Make sure that your instance is also in the same availability zone in which you have created the volume. Click on "Attach" to proceed.

![image](https://user-images.githubusercontent.com/103466963/171441492-03fdb8e2-fe49-4377-a868-3ea399c36fd1.png)



