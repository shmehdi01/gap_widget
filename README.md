# gap_widget

Gap Widget Vertical Gap and Horizontal Gap to rid out of write SizedBox

## Add Dependency 
    dependencies:
        gap_widget: ^0.0.1


## Example

    class Page extends StatelessWidget {
      const Page({Key? key}) : super(key: key);
    
      @override
          Widget build(BuildContext context) {
            return Container(
              child: Column(
                children: [
                  Text("Text 1"),
                  VerticalGap(),
                  Text("Text 2"),
                  VerticalGap(gap: 12,),
                  Row(
                    children: [
                      Text("Text 3"),
                      HorizontalGap(gap: 20,),
                      Text("Text 4")
                    ],
                  )
                ],
              ),
            );
          }
        }
    }
    
## Widgets

        VerticalGap(gap: 12.0) //default gap is 8.0
        HorizontalGap() // //default gap is 8.0


