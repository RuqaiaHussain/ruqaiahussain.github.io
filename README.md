<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To_Do List</title>

    <script src="https://cdn.tailwindcss.com"></script>
    <link href='https://cdn.boxicons.com/fonts/basic/boxicons.min.css' rel='stylesheet'>  



</head>
<body class=" bg-slate-200 w-full " dir="rtl">
    <div class=" grid grid-cols-3 h-screen ">

        <div class="bg-slate-400 xl:w-90 h-screen shadow-2xl sm:w-60 sm:text-sm   ">
            <div class="flex justify-start m-4 text-2xl font-bold shadow-lg"> 
                <i class='bxr  bx-menu-wider pl-2 pt-1'></i>  
                القائمة
            </div>
            <div class="pr-8 mt-10 md:text-lg">
                <div class=" container bg-slate-500/75  py-0.5 w-full md:min-h-14 rounded-md">
                    <div class="flex justify-start m-6 ">
                        <i class='bxr  bx-brick pl-2 pt-1 text-xl '></i> 
                        الصفحه الرئيسية 
                    
                    </div>
                </div>
                 
                <div class="hover:scale-105 py-0.5 mt-2 opacity-75 hover:rounded-md">

                    <div class="flex justify-start m-6 ">
                        <i class='bxr  bx-calendar-alt pl-2 pt-1 text-xl' ></i> 
                        التقويم 
                    </div> 

                </div>
                
                <div class="hover:scale-105 py-0.5 mt-2 opacity-75 hover:rounded-md">
                    
                    <div class="flex justify-start m-6">
                        <i class='bxr  bx-arrow-down-left-stroke pl-2 pt-1 text-xl'></i> 
                         الدعم 
                    </div>

                </div>
               
                <div class="hover:scale-105 py-0.5 mt-2 opacity-75 hover:rounded-md">
                     
                    <div class="flex justify-start m-6">
                        <i class='bxr  bx-trash pl-2 pt-1 text-xl'></i> 
                         محذوقة مؤخراً  
                    </div>

                </div>
                

            </div>
            

        </div>




        <div class="col-span-2  overflow-y-auto object-cover sm:pl-2 sm:ml-2">
            
            <div class="xl:text-5xl sm:text-lg md:text-xl lg:text-2xl  pt-3  mb-18 shadow-lg pb-3">    قائمة المهام </div>
            <div class=" flex space-x-12">
                <div class="continer w-full  h-2/5  bg-slate-300 rounded-lg ml-32 sm:text-lg  ">
                    <div class=" flex justify-center text-lg xl:text-2xl font-bold pt-2 pb-8">تذكير جديد</div>
                    
                    
                        <div class="  pr-4 mb-5 font-bold flex  items-center justify-center   "> 
                        <label class="text-right flex items-center"> العنوان</label>
                        <input type="text" class="rounded-md  bg-white w-full ml-4  mr-6 text-right text-ms pr-2 h-10 hover:bg-neutral-200 duration-400" placeholder="اسم العنوان"> 
                        </div>
    
                    
                    <div class=" flex justify-end pr-4 mb-5 font-bold">
                      <label class="text-right my-6"> التفاصيل </label> 
                        <input type="text" class="rounded-md  bg-white w-full  h-20 ml-4  text-ms mr-3 text-right pr-2 hover:bg-neutral-200 duration-300" placeholder="مـلاحظـات " > 
                    </div>
    
    
                    <div class=" flex justify-end items-center pr-4 mb-5 font-bold"> 
                        <label class="text-right"> منذ </label> 
                        <input type="datetime-local" class="rounded-md  bg-white w-full h-10 ml-4 pl-4 text-ms mr-12 text-right pr-2 hover:bg-neutral-200 duration-300"  >
                    </div>
    
                    <div class=" flex justify-end items-center pr-4 mb-5 font-bold">
                        <label class="text-right"> الى </label> 
                        <input type="datetime-local" class="rounded-md  bg-white w-full h-10 ml-4 pl-4 text-ms mr-12 text-right pr-2 hover:bg-neutral-200 duration-300"  >
                    </div>
                    
    
                    
                    <div class="flex justify-between ">
                        <div class="  pr-4 mb-5 font-bold"> تذكير </div>
                        <i class='bxr  bxs-toggle-left  pl-4 pt-1 text-4xl text-green-700  ' ></i>
                    </div>
                    
    
                    <div class="flex justify-center ">
    
                        <button class=" w-15.5 bg-green-700 hover:bg-green-900 rounded-full h-12 flex items-end text-white text-3xl font-bold px-5 py-2.5 mb-3 "> + </button>
    
                    </div>
    
    
                    
                </div>

                
            </div>
            

    

            <div class="block md:flex space-x-12 mt-12">
                <div class="continer min-w-2/5 h-2/5 bg-slate-300 rounded-lg mb-12">
                    <div class=" flex justify-center text-xl font-bold pt-2 pb-5"> التذكيرات </div>
                    
                    <div class="flex justify-between">
                        <div class="  pr-4 mb-5 font-bold flex justify-end  "> 
                            <input type="radio" class="w-6 h-6 ml-8 ">

                            امتحان مد
                        
                        </div>
                    <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 

                    </div>
                        
    
                    <div class="flex justify-between">
                        <div class=" flex justify-end pr-4 mb-5 font-bold ">
                            <input type="radio" class="w-6 h-6 ml-8">
                            دين 50                             
                        </div>
                    <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 


                    </div>
                    
    
                    <div class="flex justify-between">
                        <div class=" flex justify-end pr-4 mb-5 font-bold ">
                           <input type="radio" class="w-6 h-6 ml-8">
                            قراءة قرأن
                           
                       </div>
                        <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 

                    </div>
                    
                    <div class="flex justify-between">
                        <div class=" flex justify-end pr-4 mb-5 font-bold ">
                           <input type="radio" class="w-6 h-6 ml-8">
                            عيد ميلاد 
                           
                       </div>
                        <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 
        
                    </div>

                    <div class="flex justify-center pt-23">
    
                        <button class=" w-15.5 bg-red-700  hover:bg-red-900 rounded-full h-12 flex items-end text-white text-4xl font-bold px-5.5 py-2.5 mb-3 "> - </button>

    
                    </div>
                    
                </div>
                <div class="continer  min-w-2/5  h-2/5 bg-slate-300 rounded-lg">
                    <div class=" flex justify-center text-xl font-bold pt-2 pb-5"> المكتملة </div>
                    
                    <div class="flex justify-between">
                        <div class="  pr-4 mb-5 font-bold flex justify-end line-through "> 
                            <input type="radio" checked class="w-6 h-6 ml-8">
                            طبيب اسنان
                        
                        </div>
                    <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 

                    </div>
                        
    
                    <div class="flex justify-between">
                        <div class=" flex justify-end pr-4 mb-5 font-bold line-through">
                            <input type="radio" checked class="w-6 h-6 ml-8">
                            كورس برمجه
                            
                        </div>
                    <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500 hover:text-neutral-950'></i> 
                    </div>
                    
    
                    <div class="flex justify-between">
                        <div class=" flex justify-end pr-4 mb-5 font-bold line-through">
                            <input type="radio" checked class="w-6 h-6 ml-8">
                            قراءة كتاب
                                                        
                        </div>
                        <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 
        
                    </div>
                    
                    <div class="flex justify-between">
                        <div class=" flex justify-end pr-4 mb-5 font-bold line-through">
                           <input type="radio" checked class="w-6 h-6 ml-8">
                            سورة الملك
                           
                       </div>
                        <i class='bxr  bx-trash pl-2 pt-1 text-xl ml-3 text-neutral-500  hover:text-neutral-950'></i> 
        
                    </div>
                    
    
                    
                    
                    
    
                    <div class="flex justify-center pt-23">
    
                        <button class=" w-15.5 bg-red-700 hover:bg-red-900 rounded-full h-12 flex items-end text-white text-4xl font-bold px-5.5 py-2.5 mb-3 "> - </button>

    
                    </div>
    
    
                    
                </div>
            </div>
                

            
            

        </div>




    </div>
    


    
    
    
</body>
</html>
