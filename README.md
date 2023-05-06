# .NetAntiCrack

this is anticrack dll , it have some features like it continusely scanning for id dnspy, processmanager etc running or not, if found process 
its gonna close both app. And also its have anti harmony, so dont by affraid about your app its not gonna be patched by 0harmony :)
just add this 2 line 
Thread AntiCrack = new Thread(AntiCrack_Eaminx.AntiCrack_Eaminx.AntiCrack);
            AntiCrack.Start();
            
in your program.cs
like this 

            Thread AntiCrack = new Thread(AntiCrack_Eaminx.AntiCrack_Eaminx.AntiCrack);
            AntiCrack.Start();
            Application.EnableVisualStyles();
            Application.SetCompatibleTextRenderingDefault(false);
            Application.Run(new Form1());
