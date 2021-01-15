# A sample Gemfile
source "https://rubygems.org"

# gem "rails"

def oxford_comma(array)
    if array.length == 1
        return "#{array[0]}"
    elsif array.length == 2
        return array.join("and")
    else array.length >= 3
        last_item = "and #{array[-1]}"
        array.pop
        array.push(last_item)
        return array.join(",")
    end
end