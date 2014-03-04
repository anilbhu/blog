class Post < ActiveRecord::Base
 attr_accessible :title, :content
 has_many :comments
 
 validates :title, :content, :presence => true
 #validates :title, :content, :lenght => {:minimum => 2}
 validates :title, :content, :uniqueness => true

end


 
