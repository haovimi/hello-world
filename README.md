# hello-world
test
#puts "Nhap thoi gian Military (vd: 1630): "
#miltime = gets.chomp

miltime="1630"
if miltime[0,2].to_i < 12
  ngay_dem="AM"
else
  ngay_dem = "PM"
end

if miltime[0,2].to_i > 12
  stantime = miltime[0,2].to_i-12
else
  stantime = miltime[0,2].to_i
end
puts stantime.abs.to_s << ":" << miltime[2,2] << ngay_dem
puts
#method
def praise_person(name,age)
    puts "I want to meet #{name} when I am #{age + 3} years old."
end

praise_person("Hoai", 25)
puts
color = "Green"
if color == "Red"
    puts "Redooo"
elsif color == "Green" #elsif ko phải elseif và nếu đúng thì dừng luôn dù mệnh đề elsif sau đó đúng
    puts "that's the one"
elsif color.class == String
    puts "oh no you didn't"
end
