# Script Example

; Comment 
+$200 ; Offset from beginning // Optional, only in beginning 
-$400 ; Offset from end       // Optional, only in beginning 

"PatchNameA" #3:00653435634525255656245251235432564564625252353 ; Signature 
+6: 8463523556      ; Sign must be present
-$04: 565634252355  ; Offsets are from last signature
-0: 56345624513513  ; Optional patches

"PatchNameB" =#1:29D841C415016031535657C1     ; Bound to previous signature
-0: 56345624513513

"PatchNameC" +$06336723 ; Offset from Base 
+$06: 8463523556    ; Sign must be present
-4: 565634252355    ; Offsets are from last signature
-0: 56345624513513  ; Optional patches
