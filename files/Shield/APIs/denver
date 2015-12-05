-- Denver API
-- Features:
-- * Center Printing and SlowPrinting
-- * Game-related functions
-- * And More!

function center(y,string)
  local w,h = term.getSize()
  local x = (w/2)-(#string/2)
  term.setCursorPos(x,y)
  print(string)
end

function centerSlow(y,string)
  local w,h = term.getSize()
  local x = (w/2)-(#string/2)
  term.setCursorPos(x,y)
  textutils.slowPrint(string)
end
