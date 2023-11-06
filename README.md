# who_am_i-

<Introduce yourself through assembly>

.LC0:

        .string "\352\271\200\354\240\225\354\234\244"

.LC1:

        .string "17"

.LC2:
        
        .string "dev"

main:

        push    rbp
       
        mov     rbp, rsp
        
        mov     edi, OFFSET FLAT:.LC0
        
        mov     eax, 0
        
        call    printf
        
        mov     edi, OFFSET FLAT:.LC1
        
        mov     eax, 0
        
        call    printf
        
        mov     edi, OFFSET FLAT:.LC2
        
        mov     eax, 0
        
        call    printf
        
        mov     eax, 0
        
        pop     rbp
        
        ret
