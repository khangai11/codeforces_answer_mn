Solution: Орой болгонд өнгөнөөс хамаарч 1 эсвэл -1 гэсэн утга онооно(val[]). Хэрвээ өөрийнх нь болон өөрөөс доор байрлах оройнуудын утгын нийлбэр нь 0 байх оройнуудын тоог нь олох бодлого болно.
parent[] -ийг хувиргаад child[][] болгож хувиргаад, доорхи фунцийг ажиллуулахад хариу нь олдоно.

func(i):
    b = val[i]
    for(i-ийн бүх child j-н хувьд доорхи үйлдлийг хийнэ)
        b += func(j)
    
    хэрвээ b нь 0-тэй тэнцүү бол хариултаа 1-ээр нэмнэ.

[implementation ](https://codeforces.com/contest/1676/submission/156697029)