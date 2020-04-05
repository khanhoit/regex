#   \b Khớp với từ ở ranh giới vị trí giữa ký tự và không phải ký tự hoặc vị trí(bắt đầu/ kết thúc chuỗi);

### Ví dụ
`
    /\b44\b/g
`

Chuối khới: ab <u>44</u> sheets of a4

`
    /s\b/g
`

Chuỗi khớp: ab 44 sheet<u>s</u> of a4

`
    /\bs/g
`

Chuỗi khớp: ab 44 <u>s</u>heets of a4

`
    /\b[as]/g
`

Chuỗi khớp: <u>a</u>b 44 <u>s</u>heets of <u>a</u>4