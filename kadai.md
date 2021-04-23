@startuml

(*) --> "体力＝１０"
--> if"体力＜＝２０" then
-->[true]"宿に泊まる"
else
-->[false]"頑張ってレベル上げる"
(*)
stop

@enduml
