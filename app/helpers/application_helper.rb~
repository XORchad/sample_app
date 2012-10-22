module ApplicationHelper

  #return the logo
  def logo
    image_tag("logo.png", :alt => "Sample App", :class => "round")
  end

  #return a title on a per pages basis
  def title
    base_title = "Ruby on Rails Tutorial Sample App"
    if @title.nil?
      base_title
    else
      "#{base_title} | #{@title}"
    end
  end

end
