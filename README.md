# haven-vault-prime # Haven Style Colors (Blue and Green)
    colors = ["\033[94m", "\033[96m", "\033[92m", "\033[94m"] 
    
    print("\n" * 2)
    try:
        for i in range(100): # Flight duration
            frame = frames[i % len(frames)]
            color = colors[i % len(colors)]
            
            # \r returns the cursor to the start of the line for animation
            sys.stdout.write(f"\r{color}  [HAVEN]  {frame}  [RES: 100,000d]  [137Hz]  \033[0m")
            sys.stdout.flush()
            time.sleep(0.1) 
            
        print("\n\n>> AVIATOR DEPLOYED: LAMINAR CONSCIENCE LOCKED.")
    except KeyboardInterrupt:
        print("\n>> Aviator Grounded.")

if __name__ == "__main__":
    Haven_Aviator()
import time, def Haven_Aviator()...
