# Push-complex-data-in-Vector-Rust-
fn main() {
  
    //    let v=vec![3,4,5,6,7];
    //     println!("{}",&v[0]);
 
         let mut v:Vec<(String,i32)>;
         v=vec![
             ("Aqib".to_string(),21)
         ];
         println!("{:#?}", v);

    // You can add your complex data by push method       
           v.push(("Zeeshan".to_string(),22));
             println!("{:?}", v);
 }
