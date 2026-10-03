# food-menu-cpp
A Simple beginner level C++ program to create a restaurant menu.
#include<iostream>
using namespace std;
class listofitems{
    public:
    int choice=0;
    int vegchoice=0;
    int nonvegchoice=0;
    

     
        listofitems(){
      while(true){
        cout<<"********************************************"<<endl;
        cout<<"**********Welcome to our Resturant**********"<<endl;
        cout<<"********************************************"<<endl;
        cout<<"1. Veg"<<endl;
        cout<<"2. Non-Veg"<<endl;
        cout<<"3. Exit"<<endl;
        cout<<"Enter Your Choise:";
        cin>>choice; 
        if(choice>=1 && choice<=2){
             cout<<"Please select your choice from the menu"<<endl;
        }
        else if (choice==3){
                cout<<"\n"<<endl;
                break;
            }
        
        else{
            cout<<"Invalid Input"<<endl;
            break;
        }
    
 //menu showing function..
    switch(choice){
    case 1:
        cout<<"1. Veg Biryani"<<endl;
        cout<<"2. Veg Pulao"<<endl;
        cout<<"3. Veg Fried Rice"<<endl;
        cout<<"4. Veg Curry"<<endl;
        cout<<"5. Dosa"<<endl;
        cout<<"6. Idly"<<endl;
        cout<<"7. Veg Sandwich"<<endl;
        cout<<"8. Veg Pizza"<<endl;
        cout<<"9. Veg Burger"<<endl;
        cout<<"10. Sambharsaadham"<<endl;
        cout<<"*******************************"<<endl;
        cout<<"Please Enter Your Choise:";
        cin>>vegchoice;break;
        
   
    case 2:
        cout<<"1. Chicken Biryani"<<endl;
        cout<<"2. Mutton Biryani"<<endl;
        cout<<"3. Fish Curry"<<endl;
        cout<<"4. Chicken Curry"<<endl;
        cout<<"5. Mutton Curry"<<endl;
        cout<<"6. Chicken Fried Rice"<<endl;
        cout<<"7. Fish Fry"<<endl;
        cout<<"8. Chicken Sandwich"<<endl;
        cout<<"9. Chicken Pizza"<<endl;
        cout<<"10. Chicken Burger"<<endl;
        cout<<"*******************************"<<endl;
        cout<<"Please Enter Your Choise:";
        cin>>nonvegchoice;break;
        default:
        cout<<"Invalid choice"<<endl;
    
}
       if(choice==1){ switch(vegchoice){
            case 1:
                cout<<"You have selected Veg Biryani"<<endl;
                cout<<"Price: Rs. 150"<<endl;
                cout<<"Please enter the quantity: ";
                int quantity;
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Biryani"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Quantity: "<<quantity<<endl; 
            cout<<"Total price: Rs. "<<quantity*150<<endl;
            cout<<"****************************"<<endl;

            break;
        case 2:
            cout<<"You have selected Veg Pulao"<<endl;
            cout<<"Price: Rs. 120"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Pulao"<<endl;
            cout<<"Price: Rs. 120"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*120<<endl;
            cout<<"****************************"<<endl;
            break;
        case 3:
            cout<<"You have selected Veg Fried Rice"<<endl;
            cout<<"Price: Rs. 100"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Fried Rice"<<endl;
            cout<<"Price: Rs. 100"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*100<<endl;
            cout<<"****************************"<<endl;
            break;
        case 4:
            cout<<"You have selected Veg Curry"<<endl;
            cout<<"Price: Rs. 130"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Curry"<<endl;
            cout<<"Price: Rs. 130"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*130<<endl;
            cout<<"****************************"<<endl;
            break;
        case 5:
            cout<<"You have selected Dosa"<<endl;
            cout<<"Price: Rs. 80"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Dosa"<<endl;
            cout<<"Price: Rs. 80"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*80<<endl;
            cout<<"****************************"<<endl; 
            break;
        case 6:
            cout<<"You have selected Idly"<<endl;
            cout<<"Price: Rs. 60"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Idly"<<endl;
            cout<<"Price: Rs. 60"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*60<<endl;
            cout<<"****************************"<<endl;
            break;
        case 7:
            cout<<"You have selected Veg Sandwich"<<endl;
            cout<<"Price: Rs. 100"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Sandwich"<<endl;
            cout<<"Price: Rs. 100"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*100<<endl;
            cout<<"****************************"<<endl;
            break;
        case 8:
            cout<<"You have selected Veg Pizza"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Pizza"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*150<<endl;
            cout<<"****************************"<<endl;
            break;
        case 9:
            cout<<"You have selected Veg Burger"<<endl;
            cout<<"Price: Rs. 120"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Veg Burger"<<endl;
            cout<<"Price: Rs. 120"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*120<<endl;
            cout<<"****************************"<<endl;
            break;
        case 10:
            cout<<"You have selected Sambharsaadham"<<endl;
            cout<<"Price: Rs. 100"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Sambharsaadham"<<endl;
            cout<<"Price: Rs. 100"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*100<<endl;
            cout<<"****************************"<<endl;
            break;
            default:
            cout<<"Invalid Input"<<endl;

    
}
       }
        else switch(nonvegchoice){
            case 1:
                cout<<"You have selected Chicken Biryani"<<endl;
                cout<<"Price: Rs. 200"<<endl;
                cout<<"Please enter the quantity: ";
                int quantity;
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Chicken Biryani"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*200<<endl;
            cout<<"****************************"<<endl;
            break;
        case 2:
            cout<<"You have selected Mutton Biryani"<<endl;
            cout<<"Price: Rs. 250"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Mutton Biryani"<<endl;
            cout<<"Price: Rs. 250"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*250<<endl;
            cout<<"****************************"<<endl;
            break;
        case 3:
            cout<<"You have selected Fish Curry"<<endl;
            cout<<"Price: Rs. 180"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Fish Curry"<<endl;
            cout<<"Price: Rs. 180"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*180<<endl;
            cout<<"****************************"<<endl;
            break;
        case 4:
            cout<<"You have selected Chicken Curry"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Chicken Curry"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*200<<endl;
            cout<<"****************************"<<endl;
            break;
        case 5:
            cout<<"You have selected Mutton Curry"<<endl;
            cout<<"Price: Rs. 250"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Mutton Curry"<<endl;
            cout<<"Price: Rs. 250"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*250<<endl;
            cout<<"****************************"<<endl;
            break;
        case 6:
            cout<<"You have selected Chicken Fried Rice"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Chicken Fried Rice"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*150<<endl;
            cout<<"****************************"<<endl;
            break;
        case 7:
            cout<<"You have selected Fish Fry"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Fish Fry"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*200<<endl;
            cout<<"****************************"<<endl;
            break;
        case 8:
            cout<<"You have selected Chicken Sandwich"<<endl;
            cout<<"Price: Rs. 120"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Chicken Sandwich"<<endl;
            cout<<"Price: Rs. 120"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*120<<endl;
            cout<<"****************************"<<endl;
            break;
        case 9:
            cout<<"You have selected Chicken Pizza"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Chicken Pizza"<<endl;
            cout<<"Price: Rs. 200"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*200<<endl;
            cout<<"****************************"<<endl;
            break;
        case 10:
            cout<<"You have selected Chicken Burger"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Please enter the quantity: ";
            cin>>quantity;
            cout<<"\n"<<endl;
            cout<<"***********Bill************"<<endl;
            cout<<"Product: Chicken Burger"<<endl;
            cout<<"Price: Rs. 150"<<endl;
            cout<<"Quantity: "<<quantity<<endl;
            cout<<"Total price: Rs. "<<quantity*150<<endl;
            cout<<"****************************"<<endl;
            break;
            default:
            cout<<"Invalid Input"<<endl;
    
        }

    }

     }

};
class thanks{
    public:
    thanks(){
        cout<<"\n"<<endl;
        cout<<"********************************************"<<endl;
        cout<<"**********Thank you for visiting************"<<endl;
        cout<<"********************************************"<<endl;
    }
};
int main(){
    listofitems obj;
    thanks t;

    return 0;
}