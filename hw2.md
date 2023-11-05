<h1>hw2</h1>

```swift

import SwiftUI
struct ContentView: View{
    @State var count:Int = 0
    var arr = ["石頭","剪刀","布"]
    var body: some View{
        VStack{
            Text(arr[count])
                .padding(.all,10)
                .frame(width: 150, height: 120, alignment: .center)
                .font(.system(size: 50))
            Button(action: {
                count = Int.random(in: 0..<3)
            }, label: {
                Text("Go")
                    .padding(.all,10)
                    .frame(width: 300, height: 100, alignment: .center)
                    .font(.system(size: 50))
                    .background(Color.purple)
                    .foregroundColor(.white)
                    .border(Color.purple, width: 5)
                    .cornerRadius(20)
            })
        }
    }
}




```

<img src="https://raw.githubusercontent.com/BOBOGUAGUA428/s1101436_swiftui/main/IMG_0022.jpeg">
