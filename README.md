# EBS_Lab
# Create the Amazon EBS Volume

In the left menu of the EC2 dashboard select the Volume link in the Elastic Block Store section.

![image](https://user-images.githubusercontent.com/103466963/171442936-8ee4a1b2-34cf-4602-90cc-797be4d6c6b5.png)

Click on create volume

You can specify the size of your disk. Remember that you only have 30 Gb for your Free Tier. 
Once you click on create volume, it takes you to the volume settings, where you get to specifiy the kind of EBS volume you want to attach to your instance, your disc size , region etc.

![image](https://user-images.githubusercontent.com/103466963/171444481-4d481bae-89d4-4e94-b08f-a0ab70c03f00.png)

Click on create Volume as shown below to create your first EBS Volume

![image](https://user-images.githubusercontent.com/103466963/171444799-c2008a78-d803-4f83-ac65-0241b93ec67d.png)

We have been able to create our first EBS (standard) with a disc size of 20GiB
To name our EBS volume, click on the small square with a pen, call it ‘myFirstEBS’, then click on save changes

![image](https://user-images.githubusercontent.com/103466963/171445077-df9ec931-dc27-436a-99c3-ed3c1d4bc1c0.png)

# Attach the EBS Volume to the EC2 Instance

Your volume is now available but not yet attached to your EC2 instance. So, for the moment, it is available but not usable by your instance.
In order to attach it your instance, Select the EBS volume you just created and click on action, then >Attach Volume men

Once you click on attach volume it takes you to the next step below which is to select the instance to which you will like the EBS volume to be attached to,
Once the instance has been selected, gp ahead and click on attach volume

![image](https://user-images.githubusercontent.com/103466963/171446157-8af138f7-7f31-40ee-9eb0-004234e958b5.png)

From the image below you can see that we have been able to succefully attach our EBS volume to An EC2 instance . 

![image](https://user-images.githubusercontent.com/103466963/171446399-a4cb0412-76a9-4499-9c4c-6f22b73ebe50.png)

# In Review
You created a Standard EBS volume  and 
Attached the Volume to an EC2 instance
