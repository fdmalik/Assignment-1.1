# Assignment-1.1

        Dim mName As String = ""
        Dim mId As Integer = 0
        Dim moreInfo As Char = "Y"

        FileOpen(1, "c:\Assignment 1\mRec.txt", OpenMode.Output)


        While moreInfo = "Y"

            Console.Write("Enter the member`s name : ")
            mName = Console.ReadLine
            Console.Write("Enter the members`s ID number : ")
            mId = Console.ReadLine

            WriteLine(1, mName)
            WriteLine(1, mId)


            Console.Write("Would you like to add any more records?(Y/N) : ")
            moreInfo = Console.ReadLine

        End While

        FileClose(1)
