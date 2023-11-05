<h1>hw3</h1>

```swift
import SwiftUI 
struct ContentView: View{
    var body:some View{
        VStack{
            TitleView()
            HStack{
                ZStack{
                    FloorView2(imageName:"1")
                    Text("1480")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 33,y:23)
                    
                }
                ZStack{
                    FloorView2(imageName:"2")
                    Text("1680")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 33,y:23)
                    
                }
                ZStack{
                    FloorView2(imageName:"3")
                    Text("1180")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 34,y:41)
                    
                }
            }
            HStack{
               
                ZStack{
                     FloorView2(imageName:"4")
                    Text("1680")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 33,y:23)
                    
                }
                ZStack{
                    FloorView2(imageName:"5")
                    Text("420")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 35,y:23)
                    
                }
                ZStack{
                    FloorView2(imageName:"6")
                    Text("420")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 35,y:23)
                    
                }
            }
            HStack{
                ZStack{
                    FloorView2(imageName:"7")
                    Text("2680")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 17,y:48)
                    
                }
                ZStack{
                    FloorView2(imageName:"8")
                    Text("2380")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 29,y:48)
                    
                }
                ZStack{
                    FloorView2(imageName:"9")
                    Text("2980")
                        .font(.system(size:10))
                        .foregroundColor(.black)
                        .padding(.all,5)
                        .background(Color.gray)
                        .opacity(0.7)
                        .offset(x: 32,y:43)
                    
                }
            }
        }
    }
}

struct TitleView: View{
    var body: some View{
        VStack(alignment:.center,spacing:2){
            Text("Tony的")
                .font(.system(size:30))
            Text("收藏櫃").font(.title)
                .foregroundColor(Color(red: 29/255,green: 40/255, blue: 192/255))
        }
    }
}
struct FloorView1: View{
    var imageName:String
    var body: some View{
        VStack{
            Image(imageName)
                .resizable()
                .aspectRatio(contentMode:.fit)
                .frame(width: 100,height: 150,
                       alignment: .center)
            Text(imageName.capitalized)
                .fontWeight(.bold)
                .font(.system(size: 20))
            
        }.padding(.all,2)
    }
}

struct FloorView2: View{
    var imageName:String
    var body: some View{
        VStack{
            Image(imageName)
                .resizable()
                .aspectRatio(contentMode:.fit)
                .frame(width: 100,height: 150,
                       alignment: .center)
            Text(imageName.capitalized)
                .fontWeight(.bold)
                .font(.system(size: 20))
            
        }.padding(.all,2)
    }
}

struct FloorView3: View{
    var imageName:String
    var body: some View{
        VStack{
            Image(imageName)
                .resizable()
                .aspectRatio(contentMode:.fit)
                .frame(width: 100,height: 150,
                       alignment: .bottom)
            Text(imageName.capitalized)
                .fontWeight(.bold)
                .font(.system(size: 20))
        }
    }
}
extension UIScreen{
    static let screenWidth = UIScreen.main.bounds.size.width
    static let screenHeight = UIScreen.main.bounds.size.height
    static let screenSize = UIScreen.main.bounds.size
}






```

<img src="https://raw.githubusercontent.com/BOBOGUAGUA428/s1101436_swiftui/main/IMG_0295.jpeg">
