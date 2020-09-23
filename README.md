<div align="center">

## Better Movement Tutorial


</div>

### Description

Teaches about using trig to move objects better and more realistically
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Dude2](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dude2.md)
**Level**          |Intermediate
**User Rating**    |2.8 (17 globes from 6 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Games](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/games__1-38.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dude2-better-movement-tutorial__1-29233/archive/master.zip)





### Source Code

```
Hey everyone! Have you ever wondered fow to get your objects to move everywhere (instead of up, down, left and right)? If so, read on!
In math, there are two functions calles Sine and Cosine. I could get into all the details on how they work, but i'm pretty sure you'll get bored. Anyway, you use them in vb as Sin(x) and Cos(x) with x being a number. To implement it in a moving sub would be like:
Sub moveit(angle as double)
x = x + sin(angle)
y = y + cos(angle)
End Sub
Go ahead, try it! You find that if you put in a degree (like 90, which should make it go to thr right), it WILL NOT WORK. That is because you need to get radians and multiply them by the degrees. That is where mist newbies screw up. To get the amount of one radian, you do this:
Const Pi = 3.14
Const Rad = 3.14 / 180
Then, we make a little change to the procedure:
Sub moveit(angle as integer)
x = x + sin(angle * rad)
y = y + cos(angle * rad)
end sub
and that is basically it.
C U Later!
Dude2
PS> Please vote for me if you think it is good/helpful!
```

