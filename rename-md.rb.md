require 'fileutils'
Dir['./*'].each do |file|
  FileUtils.mv file, file + ".md"
end
