### Callback js 

       function login(callback){
            setTimeout(() => {
                console.log("login succesfully.")

                callback()

            }, 3000);
        }

        function paid(name){
            setTimeout(() => {

                console.log("Paid succesfully "+ name)

            }, 2000);
        }

        login(()=>{
            paid("Nayeem")
        })
        
          


Callback ই আমরা agrument dite পারি না .কিন্তু ই সিস্টেম ই আমরা agrument dite parchi কিভবে?
  
খুব সহজ ..আশলে কল ব্যাক ই আম্রা akta খালি ফাংশন call krchi, trpr paid ফাংশন argument ট দিয়ে dchi .

amra jni j akta function r vtr amra argument dete pari..
       
       function empty(){
       
          name("nayeem")
           
           }

        function name(name){
             console.log("nayeem")
           }

         empty()





               
