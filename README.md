# Automatic-Tracking-Robot-Car
-The robot car uses a magnetometer to locate，and then rotate to find the target vehicle.  
-We use deep learning image to identify and position the vehicle and track the target vehicle.  
-For further accurate positioning, we use the sensor aided image recognition.  
-When the target vehicle's position changes, it can track the final target by constantly taking photos to update the route.

Here is our robot car which is setted up to a chasing.
![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38046148_133536000899573_2220456916180533248_o.jpg?_nc_cat=0&oh=430a14c13dfe1b20df8dcc6a19ff6a50&oe=5C06ED81)

# Key hardware equipment
Raspberry pi +pi camera：It is simply a tiny computer and camera.
![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38213622_133545310898642_3472910989337296896_n.jpg?_nc_cat=0&oh=905d0acfa365cf3b4785611feb7a1d1e&oe=5C038972)

Arduino：Receive target program instruction and then control the robotics car.
![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38071384_133545307565309_6017531734709501952_n.jpg?_nc_cat=0&oh=6c430013f3f6ada9a770d1c621ef07e2&oe=5BCE5540)

3D magnetometer: Can tell the heading in all orientatArduino：Receive target program instruction and then control the robotics car.

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38140452_133545320898641_4737886043213135872_n.jpg?_nc_cat=0&oh=c323b8b85550dbbcdff09263ad30c1b4&oe=5BD1E4C2)

# Communication
Arduino: Push Data  

Pi: Pull (Poll) Data


On both Arduino Mega and Raspberry Pi，Serial communication is enabled by UART(Univeral Asynchronous Receiver/Transmitter)

# Deep Learning
YOLO is a kind of deep learning algorithm.It can recognize a perticular target and know where is it in a picture. After training with our own data, it can recognize our target car and tell the robot car how to move to chase the target.

# Development Diagram
![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38085871_133550944231412_3935913085230907392_n.jpg?_nc_cat=0&oh=b8e8888e3ba9493d8f27f14cc32d764e&oe=5BD7EABE)

# Chasing Images

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38188187_133554497564390_7546405105558355968_n.jpg?_nc_cat=0&oh=3aa103530e5c8e00f6dfa134cc0c300b&oe=5C03790A)

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38149356_133554504231056_4133586352279126016_n.jpg?_nc_cat=0&oh=0ff6d76447c1b347dce2fa74e55bd546&oe=5C0848D5)

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38052805_133554510897722_2125157033605857280_n.jpg?_nc_cat=0&oh=f4ca99d5c48604cd216e042f9a62496d&oe=5C09DCB8)

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38085238_133554564231050_3564986708682342400_n.jpg?_nc_cat=0&oh=0b0ce486044fb1e98e2aeef09f6415bc&oe=5C10C8F1)

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38180757_133554584231048_9057954725818793984_n.jpg?_nc_cat=0&oh=da25ee3244e46eee8570414fcb5bd04e&oe=5C0588A0)

![alt text](https://scontent-sit4-1.xx.fbcdn.net/v/t1.0-9/38072356_133554590897714_5730707182958149632_n.jpg?_nc_cat=0&oh=68faf0eef30e9b491216282b7ae6b188&oe=5BCC5BF6)
