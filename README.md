# Challenge-B

live_loop :three do
  16.times do
    sample :drum_cymbal_closed
    sleep 0.5
  end
  stop
end


live_loop :two do
  16.times do
    sample :drum_heavy_kick
    sleep 1
  end
  stop
end


live_loop :one do
  12.times do
    sample :drum_snare_soft
    sleep 2
  end
  stop
end

sleep 24

live_loop :drum1 do
  4.times do
    sample :drum_splash_hard
    sleep 2
  end
  stop
end

live_loop :drum2 do
  16.times do
    sample :drum_cymbal_hard
    sleep 0.5
  end
  stop
end

live_loop :three do
  16.times do
    sample :drum_cymbal_closed
    sleep 0.5
  end
  stop
end

sleep 8

live_loop :three do
  16.times do
    sample :drum_cymbal_closed
    sleep 0.5
  end
  stop
end


live_loop :two do
  8.times do
    sample :drum_heavy_kick
    sleep 1
  end
  stop
end


live_loop :one do
  4.times do
    sample :drum_snare_soft
    sleep 2
  end
  stop
end
