<h1>hw1</h1>

```swift
import SwiftUI

struct ContentView: View{
    var body:some View{
        
        Image("BOBOGUAGUA")
            .resizable()
            .scaledToFit()
            .background(.white)
            .aspectRatio(contentMode: .fill)
            .overlay(
                Text("s1101436\n謝博丞").fontWeight(.heavy)
                    .lineSpacing(10)
                    .font(.system(size: 25.0))
                    .foregroundColor(.black)
                    .position(x:125,y:50)
                
            )
        
            .overlay(
                Text("帽子給我好嗎～").fontWeight(.heavy).lineSpacing(20).font(.system(size: 25.0)).foregroundColor(.white).frame(width: 350, height: 100, alignment: .center)
                    .background(Color.gray)
                    .cornerRadius(30.0)
                    .opacity(0.8)
                ,alignment: .bottom
            )
    }
}


```

<img src="https://raw.githubusercontent.com/BOBOGUAGUA428/s1101436_swiftui/main/IMG_0022.jpeg">
