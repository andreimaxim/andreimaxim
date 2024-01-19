```ruby
class About
  def enjoys
    # TODO: Add Javascript
    %w[ ruby ]
  end

  def works_for
    %w[ Throwpoint WEForum ]
  end

  def for_hire?
    works_for.empty?
  end
end
```
